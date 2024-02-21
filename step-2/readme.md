Install Node Exporter <br>
1. wget https://github.com/prometheus/node_exporter/releases/download/v1.2.2/node_exporter-1.2.2.linux-amd64.tar.gz <br>
2. tar xvfz node_exporter-1.2.2.linux-amd64.tar.gz <br>
3. sudo mv node_exporter-1.2.2.linux-amd64/node_exporter /usr/local/bin/ <br>
4. sudo nano /etc/systemd/system/node_exporter.service <br>
5. sudo useradd -rs /bin/false node_exporter <br>
6. sudo systemctl daemon-reload <br>
7. sudo systemctl start node_exporter <br>
8. sudo systemctl enable node_exporter
