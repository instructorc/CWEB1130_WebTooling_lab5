#  Dockerizing a Node.js web App - Using Docker and Docker Hub (Lab 5)
For this lab, you are going to walk through a series of steps that dockerize a basic node.js application and allows you to publish that image to your docker hub account.  This lab  requires that you already have an account at [hub.docker.com](https://hub.docker.com).  


## Requirements

### Step 1 - Create a web project and implement version control
1.  Create a folder titled **[cweb1130_lab5]**
2.  Make sure you are in the newly created directory and install git by running command **[git init]**
3.  Run the command [git pull origin lab5] to pull down the README.md file that contain instructions



### Step 2 - Configure and install Node app found at [https://nodejs.org/en/docs/guides/nodejs-docker-webapp/](https://touch4it.com/blog/end-to-end-testing-puppeteer-jest)
Follow the steps found in webpage and seek to understand what is happening at each step.  Make sure to run command **[npm audit fix]** after installing project dependencies.

### Step 3 - Push up your image to Docker Hub
1.  Make sure your stop the container from running in your local environment by running **[docker container stop <your username>/node-web-app]**.  You can also remove the container by running **[docker container rm <your username>/node-web-app]**
2.  Push up your image to docker hub by running command [ docker push <your username>/node-web-app]

	
### Step 4 - Github Repository
1.  Add Instructor as a contributor to repository by searching for **[instructorc]**
2.  Adjust README.md file at the end to include date of completion and course information.

### Step 5 - Submission
1.  Comment your name to the server.js file.
2.  Make sure your master branch is clean and push up your final changes.
3.  In Canvas, submit the URL to your repository
	

#### Github Classroom Invitation URL: https://classroom.github.com/a/RKEevvp6
