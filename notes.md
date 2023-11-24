#### Check size of installed pip packages

cd /Users/abhisheknagpurkar/DE/AirflowProject1/AirflowGettingStarted/env/lib/python3.11/site-packages
du -h -d 1 | sort -rh | grep -v "dist-info"

#### Adding local repo to github

1. Ensure local .git is added and commited
git init -b main
git add .
git commit -m "First commit"

2. Add local to remote github
git remote add origin REMOTE-URL
git remote -v
git push -u origin main

#### Connect VS to remote gcp vm
This command --> gcloud compute config-ssh generates the following which when you run in vs code adds the vm to vs code remote ssh extension
ssh centos-stream-9.us-east4-c.dataengineeringongcp-400910
