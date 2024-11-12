# LifeEasy - Setup Guide

Welcome to the LifeEasy setup guide! Follow these instructions to get LifeEasy up and running on your machine.

## Prerequisites

Before you begin, ensure you have the following software installed:

1. **Git**: Required for version control. (**mandatory**)
   - [Download and install Git](https://git-scm.com)

2. **Docker**: Essential for containerizing and managing application services. (**mandatory**)
   - [Download and install Docker](https://docs.docker.com/get-docker/)
   - The docker should have CPUs 4 and a memory of 4GB.
   - The arch should be aarch64.
3. Mail Integration - (**mandatory**)
4. [Razorpay Payment Integration](https://razorpay.com/docs/payments/server-integration/nodejs/integration-steps/#1-build-integration) (optional)
5. Rapid Api Integration (optional)

## Installation

Follow the below step to set up the client and server:

```sh install.sh```

## Configure the Environment Variables

Most of the variables are set to their default values.

1. .env.client
2. .env.server
3. .env.chat-server

## Starting the Application

To start the application, run:

```sh startup.sh```

## Shutting Down the Application

To shut down the application, run:

```sh shutdown.sh```

## Cleaning up the Application

To cleanup the application, run:

```sh cleanup.sh```

This will remove all the running containers, images, volumes, and networks in Docker.
