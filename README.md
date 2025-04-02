# Kubernetes config repo using Kustomize

## Secrets
This repo uses [git-crypt](https://www.agwa.name/projects/git-crypt/) to encrypt secrets.

Execute ```git-crypt init``` in root dir to initialize it.
Add a .gitattributes file with the configuration for the encrypted files.