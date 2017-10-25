# devops-aptitude

The following tasks will gauge an applicants ability to understand a simple web application and how to run and deploy it in a containerized environment. It is understood that there are multiple ways to achieve these tasks and there is no one-size-fits all approach.

This repository contains a simple web application that does the same thing in the following languages. You may choose to use any of the included examples, or use a different languages if desired.

- [Golang](https://golang.org/)
- [NodeJS](https://nodejs.org/en/)
- [Python](https://www.python.org/)
- [Ruby](https://www.ruby-lang.org)

## How to Use This Repository

- Clone this repository and add it to your Github profile (do not fork)
- Make changes, add files to complete the following tasks
  - Include command examples in-line in this README under each task.
  - commit and push changes
- When completed, send cloned repository link to for evaluation

### Task 1

Run the app locally using and demonstrate how to use the web application.

### Task 2

Run the app locally within [Docker](https://docs.docker.com/engine/) or other container engine.

### Task 3

Run the app using [docker-compose](https://docs.docker.com/compose/), or other container deployment framework, with [nginx](https://docs.docker.com/compose/) or other web server as a reverse proxy to the application.

### Bonus

Additional tasks to further show mastery of application deployments and understanding.

- Add an additional route to the application to return full list of gifs
- Minimize container image
- Setup [TravisCI](https://travis-ci.org), [CircleCI](https://circleci.com), or other automated continous integration to automatically build and deploy
- Add deployment files for [Rancher](http://rancher.com), [Kubernetes](https://kubernetes.io) or other container [orchestration and management framework](https://github.com/cncf/landscape).
