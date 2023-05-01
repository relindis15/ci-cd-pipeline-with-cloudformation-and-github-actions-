## ci-cd-pipeline-with-cloudformation-and-github-actions-

Create a github repository and clone it on vscode(ci-cd-pipeline-with-cloudformation-and-github-actions)

<img width="932" alt="Create repository" src="https://user-images.githubusercontent.com/114790551/234169208-46c4483e-9f25-4b96-bc1f-5cf9abbbd784.png">

Create a cloud formation template with resources like S3 that will be used for static website

Choose the language in which you want to write the template

Prepare a cloud formation template setting the different parameters for the s3 bucket

create an index.html file that we will use to host our static website, we will use an inline CSS file

Code review

Make sure there is a role add permissions to it and add user, aws fullaccess permission should be assigned to this user

<img width="917" alt="Cloudformationfull access to user" src="https://user-images.githubusercontent.com/114790551/234169376-a688cca1-e230-4f9d-b032-30c05ff8d86f.png">

Connect your aws to your github by using aws adding secretes to your github

<img width="914" alt="access and secret keys added to github" src="https://user-images.githubusercontent.com/114790551/234169471-1d13d7b2-1e85-4af6-b90a-a9750e65118d.png">

Create a folder .github and in it create a workflow folder and a yaml file inside contains your deployment script(a stage deploying your stacks and another deploying your s3 bucket)

Push to our github repository

<img width="782" alt="stack deployed" src="https://user-images.githubusercontent.com/114790551/235387928-997b0536-4802-4a0e-8fe5-47b3ed20d28f.png">

Test your pipeline

Answer the open questions

Do a clean up
