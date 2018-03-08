# GitOps Hello World Staging

GitOps [hello world](https://github.com/crowdynews/gitops-hello-world-gcb) REST API infrastructure
configuration for staging.

## Caveats

### Identity & Access Management Roles

GCP IAM requires `[PROJECT_ID]@cloudbuild.gserviceaccount.com` to have the following roles:

* Cloud Container Builder
* Kubernetes Engine Developer
