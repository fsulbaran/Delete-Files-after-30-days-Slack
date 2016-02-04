Asuming you have python installed in your computer.... ( mac os X comes with python)

1. Install the requests library

open terminal cd to the folder request and  do
> sudo python setup.py

2. Get a token from the https://api.slack.com/web

Create a web API token with your slack admin user

3.Paste the token and write down the domain inside "slack_delete.py"

4. run the script, do:

> sudo python slack_delete.py


IT will erase all files older than 30 days.

enjoy, script by @svpino
