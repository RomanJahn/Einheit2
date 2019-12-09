# Uebung5

* Link github: https://github.com/RomanJahn/Einheit2

* Link docker registry: https://hub.docker.com/repository/docker/romanjahn/nodeapp

* Weblink: http://52.155.223.169/ (see screenshots-directory)

* Screenshots in the 'screenshots' directory!

### Documentation:
Every push to this repo triggers a build and release pipeline in Azure.
The build pipeline (azureDocker.yml) creates a docker image and pushes it to dockerhub.
Then a release of this node-app is deployed to Azure Kubernetes (deployment.yml).

During the process of building, the file deployment-template.yml gets changed into a file
named deployment.yml containing the current docker image tag.

# Lab2(old)
Git-Repo-Link:
https://github.com/RomanJahn/Einheit2

Azure Links:
https://fhnw19-node-einheit2.azurewebsites.net
https://fhwn19-node-lab2prod.azurewebsites.net


Releases können nur von einem bestimmten User (mir) freigegeben werden