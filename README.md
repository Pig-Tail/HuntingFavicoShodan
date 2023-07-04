# HuntingFavicoShodan
Search phishing sites by favico


####
It is advisable to run it on a virtual env to avoid conflicts.
- For install virtualenv in python:  sudo apt install python3-virtualenv python3-venv
- For create virtualenv "virtualenv venv"
- To activate the enviroment "source venv/bin/activate"
####
pip3 install -r requirements.txt



####
USAGE
####

python3 shodanfav.py hxxp://target.com/favicon.ico

Example shodan: https://www.shodan.io/search?query=http.favicon.hash%3A124060887


Some favicons:

BBVA: http.favicon.hash:124060887