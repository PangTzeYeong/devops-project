<h1 align="center"> *(Forked Repo)* # Currency Exchange API – NodeJS </h1>

<p align="center">

<img src="https://img.shields.io/badge/made%20by-PangTzeYeong-blue.svg" >

<img src="https://badges.frapsoft.com/os/v1/open-source.svg?v=103" >

<img src="https://img.shields.io/github/stars/PangTzeYeong/sgus-devops-project">

<img src="https://img.shields.io/github/issues/PangTzeYeong/sgus-devops-project">

<img src="https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat">
</p>

<h2 align="left"> Adding a Github Telegram notifier </h2>

Set up GitHub Actions workflow that triggers telegram notification whenever there is a Push/Pull request

GitHub actions provides a workflow for user to automate certain process when certain actions are triggered

under .github/workflows/ we can find ***tg-notify.yml*** created to enable such notifications in telegram

https://cyaninfinite.com/getting-updates-from-github-via-telegram-bot/
<p> telegram username @gh_notify8888_bot => Note: a unique access ChatToken is inserted in 'Settings=>Secrets', which tells the telegram bot to notify only my particular chat_id when there is a trigger </p>

![Github_telegram_bot](tg_notifier.jpg)

<h2 align="left"> Steps in Google Cloud Shell with Editor </h2>

https://shell.cloud.google.com/

***1) Get Source***
<p> git clone https://github.com/PangTzeYeong/devops-project </p>

***2) Make changes***
<p> modify app.js in directory </p>

***3) Build Container***
<p> docker build . -t myapi </p>

***4) Run Container***
<p> docker run -d -p 8080:8080 myapi </p>

If there is an error message, there may be another (the previous?) container running on the same port. In this case use this command to kill all running containers:

<p> docker kill $(docker ps -q) </p>

curl -i http://localhost:8080/fx

Screenshot of the output for the command above
![nodejs_output](nodejs_output.png)

<h2 align="left"> Optional: what's next </h2>

***Improve Telegram bot***
<p> So that the bot can notify multiple people when there are updates to specific parts of the repository </p>

***Publish to Dockerhub***
<p> Shall sign up at https://hub.docker.com/ and get more familiar with it.. After 15days of Chinese New Year celebrations =) HUAT AH ! </p>

![River_Hongbao_Huatah](huatah.jpg)
