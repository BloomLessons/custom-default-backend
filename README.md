# Instructions
This is a starter template for [Learn Next.js](https://nextjs.org/learn).

Modified by Bloom Lessons for Kubernetes default-backend.

## Prepare the docker image
To prepare the docker image, run the following command from the root folder:
```bash
docker build -t default-backend-nextjs --platform=linux/amd64 .
```
You may substitute `default-backend-nextjs` with your own image name/tag.

Ensure you use `--platform=linux/amd64` if running on any other platform that is not using amd64. Unless you have configured your Kubernetes envionrment to use the specific platform on which you are building from. By default `amd64` is used in our tutorials.
