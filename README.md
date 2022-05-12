# freecodecamp-gitlab-ci-project
Hii Guys! In this project i have deployed a containerized application on AWS Elasticbeanstalk using GitLab CI/CD.
Steps:
1. Take the web Application code from Community.
2. Build the App through CI file and save the Artifacts of build.
3. Download the Build App and create Docker image locally or you can also create through CI file(.gitlab-ci.yml).
4. After building the image of App succesfully you can test the image by creating container and test weather App is working fine.
5. Upload or add image to your Container Registry how to add instructions are provided in Container registry itself.
6. Create variables for accessing AWS account through your GitLAb account and Deploy token for AWS to access your container registry respectively.
7. Using CD in file(.gitlab-ci.yml) Deploy App to AWS prior to this create required ebs environment in AWS.
8. Check out .gitlab-ci.yml.
