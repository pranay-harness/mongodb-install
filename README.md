# mongodb-install
This is a wrapper on peer-finder library used in the MongoDB Helm Chart

While building the Docker image, use the below command to build it in order to avoid the 
exec ./install.sh: exec format error

`docker buildx build --platform=linux/amd64 -t image-name:version .`
