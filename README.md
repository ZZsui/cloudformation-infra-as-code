# cloudformation-infra-as-code
Practice of AWS product - cloudformation, write infra as code to launch and mange network infrastructures.

## Scenario
Your company is creating an Instagram clone called Udagram. Developers pushed the latest version of their code in a zip file located in a public S3 Bucket.

You have been tasked with deploying the application, along with the necessary supporting software into its matching infrastructure.

This needs to be done in an automated fashion so that the infrastructure can be discarded as soon as the testing team finishes their tests and gathers their results.

## AWS Diagram

![Image](ZachUdagramAWS_Diagram.jpeg?raw=true)

## Commands
```
create.sh to create cloudformation stack by passing 3 parameters, stack name, config yaml, config parameters json.

update.sh to update cloudformation stack by passing 3 parameters, stack name, config yaml, config parameters json.

destroy.sh to delete the cloudformation stack by passing stack name.
```