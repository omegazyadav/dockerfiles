## Dockerize Everything 

### This directory contains bunch of dockerfile and docker compose which can be used instantly. 

### Terraform

- Build Image
```
docker image build --tag terraform:0.14.8 --build-arg BASE="hashicorp/terraform:0.14.3" --build-arg TFPLANTOOL="v0.1.0" .
```
Tag Image
```
docker tag terraform:0.14.8 omegazyadav/terraform:0.14.8
```
Publish Image
```
docker push omegazyadav/terraform:0.14.8
```

