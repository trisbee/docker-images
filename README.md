# Trisbee Docker images

Our custom images with every useful tooling which we need.
All images are stored in our AWS ECR repositories.
For access to them you have to setup your AWS credentials in your system.

## Open JDK 11

- AWS Policy: [github_actions_ecr_openjdk11](https://console.aws.amazon.com/iam/home?region=eu-central-1#/policies/arn:aws:iam::533728968241:policy/github_actions_ecr_openjdk11$jsonEditor?section=permissions)
- local build: `docker build -t trisbee/custom-owned-openjdk11 .`