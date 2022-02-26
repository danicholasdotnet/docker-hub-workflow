# docker-hub-workflow
GitHub Actions workflow to checkout your code, build it  from Dockerfile, and then push to docker.io. This happens any time you push a tag like v1.2.3, and it will push to a repository matching the github repo name, with that tag, as well as latest.
