# ubuntu.nomad-client

Hashicorp nomad setup for Ubuntu.

- https://github.com/Monadical-SAS/ubuntu.nomad-client
- https://github.com/hashicorp/nomad
- https://github.com/jovandeginste/nomad-compose
- https://www.nomadproject.io/docs/configuration/index.html

```fish
cd /opt
git clone https://github.com/Monadical-SAS/ubuntu.nomad-client
cd ubuntu.nomad-client

# Run the setup script & tweak any necessary configuration
./bin/setup
nano etc/nomad/client.hcl

# Then restart it and check its status
systemctl restart nomad
systemctl status nomad
nomad status
```
