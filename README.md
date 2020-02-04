# td-customscript-developement
## What's this?
To develop TreasureData CustomScript with python.

## How to use
build docker image  
`docker build -t waysaku/digdag-python-dev --no-cache=true /dockerfile/`

start container from image  
`docker run -it [ImageId] /bin/bash`

login current container  
`docker exec -it [Container Id] /bin/bash`

first time login, apply local environment  
`$ source .bash_profile`

first time open vim window, load all vim plugin manually  
`:call dein#install()`
