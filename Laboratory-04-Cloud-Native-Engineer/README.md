# Laboratory 04: Cloud-Native Engineer

## Mission Overview
This laboratory activity explores the shift from traditional virtualization to containerization. As part of the CloudNova Technologies team, this mission involves demonstrating the speed and efficiency of Docker by pulling, running, and managing a live, containerized Nginx web server using the KillerCoda terminal environment.

## Objectives
* Differentiate between traditional Virtual Machines (VMs) and Containers.
* Access a Docker-enabled cloud environment using KillerCoda.
* Execute fundamental Docker CLI commands.
* Pull, run, manage, and terminate a containerized application (Nginx).
* Create professional technical documentation of container operations using Markdown.

## Docker Commands Executed
* `docker --version`
* `docker info`
* `docker pull nginx`
* `docker run -d -p 8080:80 nginx`
* `docker ps`
* `docker stop <container_id>`
* `docker ps -a`
* `docker rm <container_id>`

## Skills Learned
* Deploying a fully functional web server in a matter of seconds using container images.
* Managing the complete lifecycle of a Docker container (start, stop, remove) using the Linux terminal.
* Mapping host ports to internal container ports for external network access.

## Challenges Encountered
* [Halimbawa: Figuring out the exact Container ID needed to stop and remove the container.]
* [Halimbawa: Ensuring the curl command targeted the correct localhost port setup during the detached run.]
