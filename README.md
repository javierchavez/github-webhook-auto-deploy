# Auto-update
This is a all in one package that is hopefully just drops in.


## Dependencies

* python 3
* nginx
* uwsgi
* ubuntu 16.04

## Files

`deploy.service` 
`deploy.ini`
`deploy`


## Usefull commands


sudo systemctl restart nginx.service
sudo systemctl restart uwsgi.service
sudo systemctl restart deploy.service 


## Install

1. Create a python virtual env called *deploy* and install uwsgi in the python environment.
2. 
3. 
4. 
5. sudo ufw allow 'Nginx Full'


sudo ln -s /etc/nginx/sites-available/deploy /etc/nginx/sites-enabled