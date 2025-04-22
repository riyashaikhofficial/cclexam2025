# CCL Practical Exam Task

Use this repo to perform the experiments

## Experiments Tasks
1. **EC2** : Deploy the `recipe-local` app on EC2. The app must run on PORT 80. Configuration must be done using Putty.
2. **EB** : Deploy the `recipe-local` app on Elastic Beanstalk. The app must run on PORT 3000. 
3. **RDS** : Deploy the `recipe-db` app on RDS. The app must run on PORT 5555 in EC2 and connected to RDS. Configuration must be done using Putty.
4. **S3** : Deploy the `recipe-static` app on S3.
5. **Dockerfile** : Deploy the `recipe-local` app on Docker using Dockerfile and docker run commands. The app must run on PORT 8080 on the host machine. Base image to be used is `node:alpine`.
6. **docker-compose** : Deploy the `recipe-db` app on Docker using docker-compose.yml file. The app must run on PORT 8081 on the host machine.
7. **Dockerfile/docker-compose** : Deploy the `recipe-static` app on Docker using Dockerfile/docker-compose.yml file. The app must run on PORT 8082 on the host machine.