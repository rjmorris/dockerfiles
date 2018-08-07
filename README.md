This repository contains dockerfiles for utilities and programming environments.

All dockerfiles are set up so that the working directory is `/code` and is owned by a non-root user with UID=1000. The name of the non-root user is `user` unless the base image already created a user for us, in which case the user name is the one created in the base image.

The available dockerfiles are:

- [r-core](r-core/) - `R` interpreter and common packages.
