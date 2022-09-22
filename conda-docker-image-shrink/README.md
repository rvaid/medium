This project contains dockerfiles to build docker images consisting of conda based environments. We have two dockerfiles here. Both the files are aimed at building python 3.9 environment with boto3 installed. The only difference is the size of the resultant image.

**Dockerfile-original**  - here image will have both environment as well as conda package manager installed.

**Dockerfile-shrink** - here image will have only environment installed. The size of the image is almots 60% lesser than that of the above image.

To build an image use the following command:

> docker build -f [dockerfile-name] -t [image-name] .
