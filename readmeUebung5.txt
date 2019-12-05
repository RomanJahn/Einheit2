Link github: https://github.com/RomanJahn/Einheit2

Link docker registry: https://hub.docker.com/repository/docker/romanjahn/nodeapp

Weblink: http://52.155.223.169/ (see screenshots-directory)

Documentation:
Every push to this repo triggers a build and release pipeline in Azure.
The build pipeline (azureDocker.yml) creates a docker image and pushes it to dockerhub.
Then a release of this node-app is deployed to Azure Kubernetes (deployment.yml).

 