# Trisbee Docker images

Our custom images with every useful tooling which we need.
All images are stored in our AWS ECR repositories.
For access to them you have to setup your AWS credentials in your system.

## Open JDK 11

- AWS User: [Custom-Owned-Images](https://console.aws.amazon.com/iam/home?region=eu-west-1#/users/Custom-Owned-Images?section=permissions)
- AWS public ECR: [Custom-Owned-Openjdk11](https://gallery.ecr.aws/j8x2y0e0/custom-owned-openjdk11)
- local build: `docker build -t trisbee/custom-owned-openjdk11 .`
- open container: `docker run -it trisbee/custom-owned-openjdk11 sh`
