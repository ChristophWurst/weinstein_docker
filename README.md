# wiwu_docker
Docker composition files for www.winzerhof-wurst.at

## Manual steps

* web: chown www-data:www-data /var/www/storage
* web: ln -s /var/www/storage/app_public/ storage
