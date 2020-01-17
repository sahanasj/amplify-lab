# Build a Photo-Sharing Web App with AWS Amplify and AWS AppSync

We'll use React to build a data-driven web app that lets users upload photos to secure photo galleries. We'll use AWS AppSync to get up and running quickly with a GraphQL API that backs our data in Amazon DynamoDB. In addition, we'll demonstrate how to use the AWS Amplify library to authenticate users, communicate with our API, and manage photo uploads. Finally, we add in AI-powered object tagging using Amazon Rekognition, allowing users to discover photos without any manual data entry.

# PREREQUISITES

* Create an AWS account/Use your Existing AWS Account <br>
* Create a Cloud9 Workspace/Your Dev Environement <br>
* Installs & Configs (Node.JS, AWS Amplify CLI, React APP) <br>

Reference LinkS:

**React APP** - https://reacttraining.com/react-router/web/guides/quick-start  <br>
**AWS Amplify Authentication** - https://aws-amplify.github.io/docs/js/authentication  <br>
https://aws-amplify.github.io/ <br>


Step 1: In your Environment install the components required:

# Update the AWS CLI <br>
pip install --user --upgrade awscli <br>

# Install and use Node.js v8.11 (to match AWS Lambda) <br>
nvm install 12.13.0 <br>
nvm alias default 12.13.0 <br>
node --version

# Install the AWS Amplify CLI
npm install -g @aws-amplify/cli

# Install jq
sudo yum install jq -y




