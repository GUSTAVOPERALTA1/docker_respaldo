# Install PHP
```bash
FROM php:7.4-cli
COPY . /usr/src/myapp
WORKDIR /usr/src/myapp
CMD [ "php", "./your-script.php" ]
```

# Create image
```bash
docker build -t my-php-app .
docker run -it --rm --name my-running-app my-php-app
```

# Install SQLite3
```bash
ROM keinos/sqlite3:latest
```