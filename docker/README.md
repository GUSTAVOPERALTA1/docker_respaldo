# install pip
```bash
apt install -y python3-pip
```
# docker create image
```bash
docker build -t mi_imagen:v1 .
```

# docker save
```bash
docker save mi_imagen > mi_imagen.tar.gz
```

# docker load 
```bash
docker image load -i mi_imagen.tar.gz
```