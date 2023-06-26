#Steps: 
1 Clone this project
2 Create a new Dockerfile in the root directory
3 Check if the dockerfile build correctly
4 Run a docker run in order to check if the docker image works
5 Push the docker image


How to run the example dockerfile:

Build the docker image
‘docker build -t example-nginx .‘

Run it:
‘docker run -p 8080:80 my-nginx‘
