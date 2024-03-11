To make this docker compose run on machine boot startup
```
sudo cp bandwidth_seller_docker_compose.service /etc/systemd/system/
sudo systemctl daemon-reload
sudo systemctl enable bandwidth_seller_docker_compose
sudo systemctl start bandwidth_seller_docker_compose

```