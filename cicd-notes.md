# CI/CD Notes

## CI (Continuous Integration)
- Automatically builds Docker image on code push
- Runs tests or build validation
- Ensures code is always deployable

## CD (Continuous Deployment)
- Deploys image to server or environment
- Can be manual or automatic using certain tools

## CI/CD Flow
1. Developer pushes code to GitHub
2. GitHub Actions triggers pipeline
3. Docker image is built
4. Image is tested
5. Image is deployed to server

## Tools Used
- GitHub Actions
- Docker
- Docker Compose
