### Techtrends project 

Step 1: Creating the docker images and taging it.
Step 2: Github actions 
        1. Create a new repo
        2. push your codes to the new repo
        3. create the `techtrends-dockerhub.yml` in the `.github/workflows/` Might be created automatically when creating the github action. 
        4. Add the docker token and GitHub encrypted secrets from the project directory Goto `settings` > `secret` > `Actions` > click `New repository secret`

![Docker Secret](screenshoots/docker_secret.PNG "Docker Secret")