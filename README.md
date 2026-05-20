# StartTech DevOps Assessment

## Overview

This project implements a complete CI/CD pipeline for a Golang backend application using AWS and GitHub Actions.

## Infrastructure

* EC2 Auto Scaling Group
* Application Load Balancer
* Dockerized Golang backend
* Amazon ECR
* Terraform Infrastructure as Code

## CI/CD

GitHub Actions pipeline:

* Go build & test
* Docker image build
* Push to ECR
* Automated deployment

## Deployment

Backend application is accessible through the AWS Application Load Balancer.

## Technologies Used

* Golang
* Docker
* Terraform
* GitHub Actions
* AWS EC2
* AWS ALB
* AWS ECR
trigger pipeline fix
