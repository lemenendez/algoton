# algoton

## build image
`docker build -t algoton .`

## running container
`docker run --rm -it -p 8888:8888 algoton`

## specifing workbook folder
`docker run --rm -it -p 8888:8888 -v /mnt/data/projects/algoton/notebooks:/home/jovyan algoton`