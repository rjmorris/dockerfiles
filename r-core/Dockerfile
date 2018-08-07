FROM rocker/tidyverse:3.5.1

RUN install2.r --error --deps TRUE \
    data.table

RUN mkdir /code && chown rstudio.rstudio /code
USER rstudio
WORKDIR /code
