#### Check size of installed pip packages

cd /Users/abhisheknagpurkar/DE/AirflowProject1/AirflowGettingStarted/env/lib/python3.11/site-packages
du -h -d 1 | sort -rh | grep -v "dist-info"
