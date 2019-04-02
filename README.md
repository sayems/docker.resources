# Docker Tutorial 
My Docker examples for Developers. A collection of how to work with Docker containers and images.

Table of contents
--
- **Docker Installation**
  - [Install Docker on Linux](https://github.com/sayems/docker.resources/wiki/Docker-for-Linux)
  - [Install Docker on macOS](https://github.com/sayems/docker.resources/wiki/Docker-for-Mac)	
- **[Getting Started with Docker](https://github.com/sayems/docker.resources/wiki/Getting-Started-with-Docker)**
  - [Containers](https://github.com/sayems/docker.resources/wiki/Getting-Started-with-Docker#containers)
  - [Lifecycle](https://github.com/sayems/docker.resources/wiki/Getting-Started-with-Docker#lifecycle)
  - [Starting and Stopping](https://github.com/sayems/docker.resources/wiki/Getting-Started-with-Docker#starting-and-stopping)
  - [Information on Docker Containers, Processes and Performance](https://github.com/sayems/docker.resources/wiki/Getting-Started-with-Docker#information-on-docker-containers-processes-and-performance)
  - [Import / Export (Backup / Restore)](https://github.com/sayems/docker.resources/wiki/Getting-Started-with-Docker#import--export-backup--restore)
  - [Executing Commands](https://github.com/sayems/docker.resources/wiki/Getting-Started-with-Docker#executing-commands)
  - [Images](https://github.com/sayems/docker.resources/wiki/Getting-Started-with-Docker#images)
  - [Lifecycle of Containers (Create, Run, Build, Commit)](https://github.com/sayems/docker.resources/wiki/Getting-Started-with-Docker#lifecycle-of-containers-create-run-build-commit)
  - [Info](https://github.com/sayems/docker.resources/wiki/Getting-Started-with-Docker#info)
  - [Cleaning up](https://github.com/sayems/docker.resources/wiki/Getting-Started-with-Docker#cleaning-up)
  - [Images Created by Redirection](https://github.com/sayems/docker.resources/wiki/Getting-Started-with-Docker#images-created-by-redirection)
  - [Import/Export Container](https://github.com/sayems/docker.resources/wiki/Getting-Started-with-Docker#importexport-container)
  - [Private and Public Registries/Repositories](https://github.com/sayems/docker.resources/wiki/Getting-Started-with-Docker#private-and-public-registriesrepositories)
  - [Running a Local Registry](https://github.com/sayems/docker.resources/wiki/Getting-Started-with-Docker#running-a-local-registry)
  - [Dockerfile](https://github.com/sayems/docker.resources/wiki/Getting-Started-with-Docker#dockerfile)
  - [Layers](https://github.com/sayems/docker.resources/wiki/Getting-Started-with-Docker#layers)
  - [Links Between Containers](https://github.com/sayems/docker.resources/wiki/Getting-Started-with-Docker#links-between-containers)
  - [Volumes](https://github.com/sayems/docker.resources/wiki/Getting-Started-with-Docker#volumes)
  - [Docker Volume Lifecycle](https://github.com/sayems/docker.resources/wiki/Getting-Started-with-Docker#docker-volume-lifecycle)
  - [Volume Information](https://github.com/sayems/docker.resources/wiki/Getting-Started-with-Docker#volume-information)
  - [Exposing Ports](https://github.com/sayems/docker.resources/wiki/Getting-Started-with-Docker#exposing-ports)
  - [Security Considerations](https://github.com/sayems/docker.resources/wiki/Getting-Started-with-Docker#security-considerations)
- **Docker Compose**
- **Setup CI/CD pipeline with Docker**
  - [Setup Docker Container with Jenkins](https://github.com/sayems/docker.resources/wiki/Setup-Docker-Container-with-Jenkins)
  - [Setup Docker Container with Travis CI](https://github.com/sayems/docker.resources/wiki/Setup-Docker-Container-with-Travis-CI)
- **Deployment - AWS Elastic Beanstalk**
  - [Deploying a Single Docker Container to AWS Elastic Beanstalk](https://github.com/sayems/docker.resources/wiki/Deploying-a-Single-Docker-Container-to-AWS-Elastic-Beanstalk)
  - [Deploying a Multiple Docker Container to AWS Elastic Beanstalk](https://github.com/sayems/docker.resources/wiki/Deploying-a-Multiple-Docker-Container-to-AWS-Elastic-Beanstalk)
- **Running Docker on AWS with Terraform**
- **Running Docker on AWS EC2**
- **Deploying AWS Elastic Beanstalk applications with Terraform**
- **[Docker Example Project](https://github.com/sayems/docker.resources/tree/master/projects)**
  - [Simple Node.js app](https://github.com/sayems/docker.resources/tree/master/projects/demo)
  - [Node.js App with Express.js]()
  - [React App with Express.js](https://github.com/sayems/docker.resources/tree/master/projects/frontend)
- [Learning Resources](#learning-resources)  
- [Useful tools for Docker](https://github.com/sayems/docker.resources/wiki/Useful-tools-for-Docker)

[top](#table-of-contents)
&nbsp;


Learning Resources
--


### Course

| # | Provider                                              | Course                                                                                                                        | Price  | Length   | Prerequisites    | Source Codes                                                 |
|---|-------------------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------|--------|----------|------------------|--------------------------------------------------------------|
| 1 | [Udemy](https://www.udemy.com/)                       | [Docker Mastery: The Complete Toolset From a Docker Captain](https://www.udemy.com/docker-mastery/)                           | $11.99 | 10 hours | Terminal, Github | [Github](https://github.com/bretfisher/udemy-docker-mastery) |
| 2 | [Servers for Hackers](https://serversforhackers.com/) | [Shipping Docker](https://serversforhackers.com/shipping-docker)                                                              | $139   |          | Terminal         | [Github](https://github.com/shipping-docker/php-app)         |
| 3 | [Udemy](https://www.udemy.com/)                       | [Docker and Kubernetes: The Complete Guide](https://www.udemy.com/docker-and-kubernetes-the-complete-guide/)                  | $11.99 | 12 hours | Terminal         | [Github](https://github.com/StephenGrider/multi-k8s)         |
| 4 | [Udemy](https://www.udemy.com/)                       | [Docker Crash Course for busy DevOps and Developers](https://www.udemy.com/docker-tutorial-for-devops-run-docker-containers/) | $11.99 | 3 hours  | Terminal         |                                                              |


[top](#table-of-contents)
&nbsp;


### Books


| # | Publisher                                        | Book                                                                                                  | Price  | Pages | Resource                                              |
|---|--------------------------------------------------|-------------------------------------------------------------------------------------------------------|--------|-------|-------------------------------------------------------|
|   | [Manning Publications](https://www.manning.com/) | [Docker in Action](https://www.manning.com/books/docker-in-action)                                    | $49.99 | 304   | [Source Code](https://www.manning.com/downloads/1337) |
|   | [Manning Publications](https://www.manning.com/) | [Docker in Practice, Second Edition](https://www.manning.com/books/docker-in-practice-second-edition) | $49.99 | 384   |                                                       |


[top](#table-of-contents)
&nbsp;

### Tutorials

- [Play with Docker](https://training.play-with-docker.com/)
