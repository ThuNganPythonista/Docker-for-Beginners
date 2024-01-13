# Docker-for-Beginners 🐳

**1) Introduction**

**2) Reasons for the emergence of Docker**

**3) Distinguishing Virtual Machine (VM) and Docker**

**4) Introduction to Containers in Docker**

**5) Differentiating Dockerfile, Docker Image, and Container**

**6) Installation and hands-on testing of Docker**

**7) Demonstrating the power of Docker and docker-compose**


**Chapter 1**

This is a skill that schools often don't teach, but it is widely used by companies and real-world projects—Docker. I will demonstrate a small web application using Docker.

**Chapter 2**

For instance, if you have an app with a MSSQL database and your app is coded in PHP running on an Apache web server. After coding, when you want users to try it, you have to deploy it, and on the testing environment, you also need to install MSSQL, PHP, and Apache. It might work on your local machine, but when deploying to a web server, it might not run because they could lack libraries or certain installations. Moreover, MSSQL only runs on Windows, and if you can only run it on Linux, you won't be able to install MSSQL, posing a significant challenge to deploying it in a unified environment with the correct libraries and software.

**Chapter 3**

In the past, before Docker, people used Virtual Machines (VMs) to install Linux or Ubuntu. Docker is more efficient because it has the Docker Engine to divide resources into containers to run different apps.

As I mentioned earlier, things like MSSQL, PHP, and Apache need to be installed in specific versions to run. Docker gathers these into a container, similar to trucks carrying containers of goods. You just need to load the goods, and they will be unloaded for you. Docker bundles MSSQL, PHP, and Apache into a ready-to-use container, so you don't have to do anything, making it incredibly user-friendly.

In the simplest terms, if you have an app that requires an extremely old and complex environment to be installed, you can run it on your machine, but when you send it to others, they need to install those complex libraries and software. Therefore, when Docker consolidates everything into a container, it optimizes both the installation and deployment processes.



