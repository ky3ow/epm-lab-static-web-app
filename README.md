# EPAM Azure Fundamentals Task

This is repo for azure fundamentals task which is part of **Cloud & DevOps Fundamentals Assessment**

## Steps

- Created git [repository](https://github.com/ky3ow/epm-lab-static-web-app) on github
- Cloned repository via `git@github.com:ky3ow/epm-lab-static-web-app.git` onto my local machine
- Opened VSCode and installed **Azure Static Web Apps extension**
- Signed in to Azure from VSCode
- Opened command palette(`Ctrl+Shift+P`) and chose `Create Static Web App`, and populated following prompts

![command palette](images/image.png)
- Static web app resource is generated in Azure, `.github/workflows` automatically generated in repository

![github actions](images/image-1.png)
![pipeline complete](images/image-2.png)
![azure portal](images/image-3.png)
![website](images/image-5.png)
- Installed `Azure functions` extension
- Opened command palette and chose `Create HTTP function`
    - created function named `message`
    - modified `api/message/index.js`
    - modified `src/App.js`
- Pulled changes from github, pushed new changes
- Checking that pipeline works on push
![pipeline after push](images/image-4.png)
- Website changed

![website after push](images/image-6.png)