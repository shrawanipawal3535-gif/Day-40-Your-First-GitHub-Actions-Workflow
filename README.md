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

<img width="1049" height="751" alt="Image" src="https://github.com/user-attachments/assets/26992f59-c223-460b-95e3-48f087052816" />

## Task 3: Understand the Anatomy

## on:

Defines when the workflow runs

## jobs:

Contains all the tasks (jobs) in the workflow

## runs-on:

Specifies the machine/environment

## steps:

List of actions performed inside a job

## uses:

Used to call a pre-built action

## run:

Executes a command/script

## name: (on a step)

Gives a label/name to the step

## Task 4: Add More Steps
Update hello.yml to also:

Print the current date and time

Print the name of the branch that triggered the run (hint: GitHub provides this as a variable)

List the files in the repo

Print the runner's operating system

<img width="843" height="1012" alt="Image" src="https://github.com/user-attachments/assets/78f707d0-c9f2-4a61-9af8-174c78939cf6" />

## Task 5: Break It On Purpose

Add a step that runs a command that will fail (e.g., exit 1 or a misspelled command)

Push and observe what happens in the Actions tab

Fix it and push again

<img width="844" height="953" alt="Image" src="https://github.com/user-attachments/assets/394b2653-f7e9-45cb-b995-ba989af31d54" /> <img width="783" height="961" alt="Image" src="https://github.com/user-attachments/assets/6a5fd222-99f6-4c9c-869a-2bc7f7c041e2" />
