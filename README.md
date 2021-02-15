<h1 align="center"> **(Forked Repo)** # Currency Exchange API – NodeJS </h1>

Set up GitHub Actions workflow that triggers telegram notification whenever there is a Push/Pull request

https://cyaninfinite.com/getting-updates-from-github-via-telegram-bot/ => telegram username @gh_notify8888_bot

1: Get Source
git clone https://github.com/PangTzeYeong/sgus-devops-project

2: Make changes
modify app.js in directory

3: Build Container
docker build . -t myapi

4: Run Container
docker run -d -p 8080:8080 myapi

If there is an error message, you may have another (the previous?) container running on the same port. In this case use this command to kill all running containers:

docker kill $(docker ps -q)

curl -i http://localhost:8080/fx

https://img.shields.io/github/forks/PangTzeYeong/sgus-devops-project

Optional: Publish to Dockerhub
Shall sign up at https://hub.docker.com/ and get a little more familiar with it.. After 15days of Chinese New Year celebrations =) HUAT AH !

![River_Hongbao_Huatah](huatah.jpg)
