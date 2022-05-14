# nginx-docker-slim

This contains the files generated when running `docker-slim build nginx` against the latest version (1.21.6) of the nginx container image from DockerHub.


## Files

|File|Description|
|---|---|
|Dockerfile|Used to generate the minified container image|
|Dockerfile.fat|Reverse Engineered by DockerSlim from the DockerHub container image|
|README.md|This file|
|creport.json|The report generated by `docker-slim build`|
|nginx-apparmor-profile|The automatically generated AppArmor security profile for the minified container|
|nginx-seccomp.json|The automatically generated SecComp security profile for the minified container|
|deployment.yaml|The file that contains everything required to deploy this in Kubernetes|
