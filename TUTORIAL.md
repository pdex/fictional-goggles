# Deploying the RCS example infrastructure

## Setup project

<walkthrough-project-setup billing="true"></walkthrough-project-setup>

## Run setup script

```sh
export TUTORIAL_PROJECT_ID={{project-id}}
gcloud config set project $TUTORIAL_PROJECT_ID
./rcs-tf-setup.sh {{project-id}}

```

## Setup the terraform runner

```sh

gcloud compute ssh tf-runner --zone=us-central1-a
```
