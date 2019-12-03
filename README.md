# OpenAtlasDataLab
This repository contains a notebook setup (python+ROOT) that allows to easily play around with the open data from the ATLAS experiment. This repo is based on one that specifically focused on measuring the Z boson in Run 1 data. Use together with jupyter with python3+ROOT available, e.g. via Docker image [cohm/pyroot-notebook](https://hub.docker.com/r/cohm/pyroot-notebook).

## Instructions
With Docker, start up the lab with 
`docker run -p 3000:8080 kthatlas/opendatalab:SH1015`
This Docker image contains a snapshot of this repository, on top of [cohm/pyroot-notebook](https://hub.docker.com/r/cohm/pyroot-notebook).
The jupyter server is launched and one can start working with the notebooks. 
If you don't have access to a computer with Docker installed, you can use it in free four-hour sessions via https://labs.play-with-docker.com/.
