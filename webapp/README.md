# Create image
```bash
sudo docker build -t my-php-web-app .
```

# Run app-web
```bash
 docker run -d -p 8888:80 my-php-web-app
 sudo docker run -p 80:80 --rm -it --name my-web-app my-php-web-app:latest

```
# Stop app-web
```bash 
docker container stop "ID"
```

# Check Apache Status
sudo systemctl status apache2.service -l --no-pager