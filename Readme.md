1. Clone this repo or download with zip

2. Copy environtment from example default user and password for mysql is in .env.example
```
cp .env.example .env
```

3. Open folder git

4. Build docker from image
```
docker-compose build app
```

5. Start application in background
```
docker-compose up -d
```

6. Install library with composer
```
docker-compose exec app composer install
```

7. Run in browser
http://localhost:8004
