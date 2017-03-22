# Auto-update
This is a all in one package that is hopefully just drops in.


## Dependencies

* python 3 - use of hash functions that are specific to python 3
* nginx
* uwsgi (python)
* ubuntu 16.04 - configuration will only work for 16.04

## Configuring Files

`webhook-app.service` Used to create a service that spawns uwsgi and sets paths for python binaries.

`webhook-deploy-app/webhook-deploy-app.ini` config of actual uwsgi instance. Secret key is set here.

`nginx/webhook-deploy-app` config of nginx. Note all requests are blocked except POST.


## Usefull commands


sudo systemctl restart nginx.service
sudo systemctl restart uwsgi.service
sudo systemctl restart webhook-deploy-app.service 


## Install

1. Create a python virtual env called *deploy* and install uwsgi in the python environment.
2. 
3. 
4. 
5. sudo ufw allow 'Nginx Full'


sudo ln -s /etc/nginx/sites-available/webhook-deploy-app /etc/nginx/sites-enabled


---
Author: Javier C
