# Day-40-Your-First-GitHub-Actions-Workflow

## Task 1: Set Up
Create a new public GitHub repository called github-actions-practice

Clone it locally

Create the folder structure: .github/workflows/

<img width="1920" height="1080" alt="Image" src="https://github.com/user-attachments/assets/c8d3e3cd-0ede-4337-8c44-36e2c7a20df8" />  

## Task 2: Hello Workflow
Create .github/workflows/hello.yml with a workflow that:

Triggers on every push
Has one job called greet
Runs on ubuntu-latest
Has two steps:

Step 1: Check out the code using actions/checkout

Step 2: Print Hello from GitHub Actions!

Push it. Go to the Actions tab on GitHub and watch it run.
