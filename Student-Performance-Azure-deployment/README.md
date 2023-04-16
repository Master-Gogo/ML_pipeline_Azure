## End to End MAchine Learning Project
step:
1)create web app
2) create docker image
3)push that image to container registry (azure)
4)then image will be pull from container registry to azure web app


## Run from terminal:

docker build -t testdocker.azurecr.io/mltest:latest . # to build the docker image

docker login testdocker.azurecr.io # login on container registry

docker push testdocker.azurecr.io/mltest:latest  # to push in CR
