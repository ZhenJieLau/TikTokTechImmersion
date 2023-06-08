# assignment_demo_2023

![Tests](https://github.com/TikTokTechImmersion/assignment_demo_2023/actions/workflows/test.yml/badge.svg)

This is a simple instant messaging system for TikTok Tech Immersion Program 2023 Backend Assignment. This project is built using this demo https://github.com/TikTokTechImmersion/assignment_demo_2023 and is referred mostly from https://github.com/weixingp/tiktok-tech-immersion-2023


## Project Setup
- Programming Language: Go
- Database: Redis
- Testing (Manual): Postman
- IDE: VSCode


## Pre-Requisites
Here are the pre-requisites of this program. 
1. Go programming language (https://go.dev/)
2. Docker Desktop (I am using Windows) (https://docs.docker.com/desktop/install/windows-install/) 


To build this program on your local Docker Desktop, right click on the docker-compose.yml file and select Compose. Once it is done, you can make HTTP request(s) by calling POST localhost:8080/api/send and GET localhost:8080/api/pull using Postman. 


### Potential Error
If you are using Windows like me, you may have error composing the docker-compose.yml file. You can try one of the following:
1. add the following line to .gitattributes file
>`* text eol=lf `

2. when cloning the repo from GitHub, add --config core.autocrlf=false at the end of the command
>`git clone (github.com/repo) --config core.autocrlf=false `

refer to https://stackoverflow.com/questions/53165471/building-docker-images-on-windows-entrypoint-script-no-such-file-or-directory



