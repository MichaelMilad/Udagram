# Project Pipeline

## This Project undergoes a pipelines consisting of numerous stages, this pipeline is triggered upon code change on github at which CircleCI Listens to this change and runs its tasks before Deploying to ensure no errors exists.

## Pipeline Stages:
1. Reading Environment Variables.
2. Installing NodeJS & NPM.
3. Installing AWS CLI.
4. Installing EB ClI.
5. Installing Backend & Frontend Dependencies.
6. Building Backend & Frontend Applications.
7. Deploying Frontend to S3.
8. Deploying Backend to Elastic Beanstalk.