# hk47-config

This repository is used to have my own cluster as code. There is one prerequisite: SealedSecrets. 
Because I want to manage my cluster with GitOps, I need some form of secret management. 
The manual steps I used are documented here: https://github.com/bitnami-labs/sealed-secrets/blob/main/docs/bring-your-own-certificates.md
I've created my own certificate and used it to sign all secrets here. 
I've done this to be able to repeat the process frequently of creating and destroying my cluster.

To install the sealed secret, follow the instructions on the github page here: https://github.com/bitnami-labs/sealed-secrets

After, it's required to install the gitops operator. 