# devops-lab

```
k3d cluster create exemplo \
  --agents 3 \
  --volume /etc/ssl/certs:/etc/ssl/certs:ro \
  --port 80:80 \
  --registry-create exemplo-registry
```
