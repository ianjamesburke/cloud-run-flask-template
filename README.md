# Google Cloud Flask Template

A simple hello world starter for a flask app hosted on google cloud run with continual deployment through github pushes

# Live Demo
[https://flask-cloud-run-starter.web.app/](https://cloud-run-flask-template-535483726398.us-central1.run.app)

# Instrusctions
- clone repo (into your own github)
- create a google console account (free)
- go to https://console.cloud.google.com/run
- click connect repo
- select Continuously deploy from a repository (source or function)
- click setup with cloud build
- link your github and select cloned repo from the list
- Allow unauthenticated invocations (we are password protected)
- click save
- app should build and deploy
- new builds triggered when pushing to main
- Go to cloud run dashboard to find url
