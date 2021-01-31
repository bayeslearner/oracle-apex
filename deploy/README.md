# Notes. 

## If you plan to use local volumes. 
```bash
mkdir -p ./volumes
sudo groupadd -g 1042 docker_fg
sudo chown -R :docker_fg ./volumes
sudo chmod -R 775 ./volumes
sudo chmod -R g+s ./volumes
sudo usermod -aG docker_fg $USER

```
