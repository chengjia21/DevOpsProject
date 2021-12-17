# DevOpsProject


## Testing CI/CD

### Aims : 

1. To create a Markdown to HTML converter via Github Pages, whereby a source file in the Markdown format (index.md) can be displayed in HTML format in a browser (URL : https://chengjia21.github.io/devopspage.github.io/).

2. To have continuous integration/deployment, such that code changes made anytime to the index.md file are continuously deployed to the end user (the viewer of the Github Page)

### Steps taken:

1) Created repository for Github Pages website

2) Designated a publishing source in the repository settings (root of main branch)

3) Created a file (index.md) at the root of the publishing source

4) Added Jekyll theme to Github Pages (Merlot Theme)

5) The index.md file was successfully displayed in HTML, using the Jekyll theme (Merlot) when accessing the https://chengjia21.github.io/devopspage.github.io/ website

6) Testing: Amended the index.md file by adding a test list to see if CI/CD process is working. Also tried changing the Github Page & Repo name to see if the new title of the site would be reflected in the website's title (The red banner on top of the site). Tests successful as the code changes were deployed and shown in the HTML Page. 

7) Added screenshots to the Readme.md and images into the live Github Page site. Decorated the site with some emojis.


<br>









### Attempt on implementing CI/CD for node.js applications, using Docker, Google Cloud Shell & Github Actions


## Steps
1) Forked from github.com/hellojoechip/nodejs-api 

2) Tried creating a new workflow, using this existing workflow template to create a Docker image:

![Docker templates image](https://github.com/chengjia21/devopspage.github.io/blob/main/Assets/Screenshot%20(708).png)

Docker image
By GitHub Actions

Build a Docker image to deploy, run, or push to a registry.
Docker image logo
docker build . --file Dockerfile --tag my-image-name:$(date +%s)


3) Set up Github Secrets for the variables GCP_EMAIL, GCP_CREDENTIALS, etc

4) Attempted to try Google Cloud Shell to run/deploy the project, but was unsuccessful.


![Google Cloud Shell image](https://github.com/chengjia21/devopspage.github.io/blob/main/Screenshot%20(711).png)
