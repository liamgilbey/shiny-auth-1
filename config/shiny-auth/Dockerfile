# Utilise the shiny base image thanks to the rocker project
FROM rocker/shiny

# copy our shiny application into the docker image
COPY ./app/* /srv/shiny-sever/

# run app
CMD ["/usr/bin/shiny-server"]