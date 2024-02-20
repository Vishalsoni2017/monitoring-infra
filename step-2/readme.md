Install Node Exporter
1.wget https://github.com/prometheus/node_exporter/releases/download/v1.2.2/node_exporter-1.2.2.linux-amd64.tar.gz
2.tar xvfz node_exporter-1.2.2.linux-amd64.tar.gz
3.sudo mv node_exporter-1.2.2.linux-amd64/node_exporter /usr/local/bin/
4.sudo nano /etc/systemd/system/node_exporter.service
5.sudo useradd -rs /bin/false node_exporter
6.sudo systemctl daemon-reload
7.sudo systemctl start node_exporter
8.sudo systemctl enable node_exporter
