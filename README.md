# zervice.nomad

[Hashicorp Nomad](https://www.nomadproject.io) server setup for Ubuntu.

- https://github.com/Monadical-SAS/ubuntu.nomad-client
- https://github.com/hashicorp/nomad
- https://github.com/jovandeginste/nomad-compose
- https://www.nomadproject.io/docs/configuration/index.html

```fish
cd /opt
git clone https://github.com/Monadical-SAS/zervice.nomad
cd zervice.nomad

# Run the setup script & tweak any necessary configuration
./bin/setup
nano etc/nomad/server.hcl

# Then restart it and check its status
systemctl restart nomad-server
systemctl status nomad-server
nomad status
```
