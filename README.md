# learn-scikit

You can install the required software using anaconda or the docker image linked below.

If you are using the docker path, make sure you have docker installed - https://docs.docker.com/engine/installation/

Clone the repo and run 
```
docker run -it -p 8888:8888 -v `pwd`:/notebook -w /notebook jitto/jupyter-sklearn
```
And go to http://localhost:8888 in browser.  Start with the intro.
