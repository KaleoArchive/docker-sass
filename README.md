# docker_sass
Docker Image for Sass

# How To Using

```shell
docker run --rm -v $(pwd):$(pwd) -w $(pwd) kaleocheng/sass file.scss
```
or 

```shell
alias sass="docker run -it --rm -v \$(pwd):\$(pwd) -w \$(pwd) kaleocheng/sass"
sass --watch input.scss:output.css
```
