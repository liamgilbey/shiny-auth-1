# shiny-auth-1

![](figures/post-image.png)

Companion repo for part 1 of the shiny auth series. Refer to the [blog post](https://blog.gilakl.com/r-shiny-auth-i/) for an overview of the contents of this report.

## Building and Deploying

Create the shiny docker image with:

```bash
docker build -t shiny-auth .
```

Deploy the image with:

```bash
docker stack deploy shiny-auth -c ./config/shiny-auth/docker-compose.yml
```