# Docker-project
# HOW TO DOCKERIZE A NODE.JS APPLICATION BY TECH KELVIN #
## Please find below the recommended steps for executing this project, followed by supplementary visual documentation for reference ##

1. **Set up your Node.js application:**
+ *Connect your git terminal to your ec2 instance*
+ *Using your ec2 ip address to connect with your ssh command*
+ *Install the necessary dependencies for your application*
  
![20230626_223655](https://github.com/kelvind627/Docker-project/assets/136044631/386eb414-8ab1-494b-99a8-6c66dad25eb8)

2. **Installation of git on your ec2 instance:**
+ *Install git using the necessary command*
+ *Run this command to see the version insttaled.(git --version)*

![20230624_215452](https://github.com/kelvind627/Docker-project/assets/136044631/b021e147-a4e8-4c3b-bd82-dd0f400a7ce5)

3. **Clone the necessary file from your git hub to your local terminal:**
+ *Run the ls command to view your cloned repository*
+ *Navigate into your cloned repository by running the cd command*

4. **Create a dockerfile:**
+ *Create a new file in your project directory named Dockerfile (without any file extension)*
+ *Open the Dockerfile in a text editor and add the necessary lines*
+ *Navigate into the created Dockerfile by running the vi command*
+ *Copy and paste the codes into the Dockerfile*
+ *Save and close the Dockerfile*

![20230625_161257](https://github.com/kelvind627/Docker-project/assets/136044631/edc8b21d-92f9-465e-afb6-7d073c09cea1)

![20230625_163103](https://github.com/kelvind627/Docker-project/assets/136044631/07eec036-b1dd-45f0-8b9b-7521691373b9)

5. **Building your custom image:**
+ *Open your terminal or command prompt and navigate to your project directory*
+ *Install and run a docker-compose tool*
+ *Run the following command to build the Docker image(using the docker-compose command)*
+ *Run the docker-compose up -d to start and build your container*
+ *Verify the Docker image*
+ *Ensure that your newly built image is listed by running this command (docker images)*

6. **Access your Node.js application in a web browser:**
+ *To access this application, go to your ec2 instances*
+ *Click on the instance*
+ *Click on the security group*
+ *Click on edit inbound rules*
+ *Click on add rules and a new talbe will open up*
+ *Under the source, select anywhere*
+ *Choose custom tcp and under the port range add your port*
+ *Click on save rules*

7. **Initialize Git in your project:**
+ *Run the following commands to initialize a Git repository, add your project files, and make an initial commit*
+ *git init*
+ *git add .*
+ *git commit -m "Initial commit"*

8. **Create a GitHub repository:**
+ *Go to GitHub (https://github.com) and sign in to your account.*
+ *Click on the "New" button to create a new repository.*
+ *Provide a repository name, optional description, and choose any additional settings.*
+ *Click "Create repository" to create the new repository.*

9. **Link your local repository to the remote GitHub repository:**

