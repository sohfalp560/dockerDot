# The Commands to Copy to Terminal

### Portainer-ce

The Portainer Community Edition (CE) is a lightweight platform that effortlessly delivers containerized applications. It provides seamless management of Docker, Swarm, Kubernetes, and ACI environments.

```shell
docker volume create portainer_data 
docker run -d -p 9442:8000 -p 9443:9443 --name portainer --restart=always -v /var/run/docker.sock:/var/run/docker.sock -v portainer_data:/data portainer/portainer-ce:lts
```