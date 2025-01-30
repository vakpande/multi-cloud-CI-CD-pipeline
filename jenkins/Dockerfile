FROM jenkins/jenkins:lts
USER root

# Install AWS CLI, Azure CLI, GCP CLI
RUN apt-get update && apt-get install -y awscli azure-cli google-cloud-sdk

# Switch back to Jenkins user
USER jenkins