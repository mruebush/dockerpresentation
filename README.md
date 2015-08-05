# Docker Presentation and Demo
- Docker is a tool that can be used to create lightweight containers.
- Build out a Streaming environment with NiFi, Spark, Hadoop and Kafka
- Build out a Node.js workflow demo

## What is a container, cgroup, ?

## Docker Ecosystem
- Docker
- Boot2Docker/Machine
- Registry
- Root Registry vs user

## Installing Docker
## Using Docker (key tags)
- run
- build
- ps
- inspect docker `inspect $(docker ps -q) | grep IPA`

## Working with the Docker Registry
## Anatomy of a DockerFile
## How Much in the DockerFile vs Base Image
- Build process where things change, want to build
- Runtime where you need it to spin up fast, need a built artifact
- Base for more centrally controlled stuff
- multiple images or shell script to build?
- Should be step in DevOps flow to create

## Building a Greater Ecosystem with Docker Compose
## Docker Machine and Boot2Docker Overview
## Scaling with Docker Swarm
## Docker Workflow
- Docker Build Containers
- Going to Production

## Securing Docker Containers
## Monitoring Containers statd, logs
- ELK stack
- Monitoring tools

## Docker and Jenkins Integration
