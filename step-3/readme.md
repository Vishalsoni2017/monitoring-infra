Install Prometheus <br>
1. wget https://github.com/prometheus/prometheus/releases/download/v2.30.1/prometheus-2.30.1.linux-amd64.tar.gz <br>
2. tar xvfz prometheus-2.30.1.linux-amd64.tar.gz <br>
3. sudo mv prometheus-2.30.1.linux-amd64 /opt/prometheus  <br>
4. sudo useradd -rs /bin/false prometheus <br>
5. sudo chown -R prometheus:prometheus /opt/prometheus <br>
6. sudo nano /etc/systemd/system/prometheus.service <br>
7. sudo systemctl daemon-reload <br>
8. sudo systemctl start prometheus <br>
9. https://ip:9090

