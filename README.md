# magma_AGW_docker

### Deploy magma on the AGW_HOST

#### Do pre-installation steps

Become root user and switch directory:

```bash
sudo su
cd /root
```

Copy your `rootCA.pem` file from orc8r to the following location:

```bash
mkdir -p /var/opt/magma/certs
vim /var/opt/magma/certs/rootCA.pem
```
