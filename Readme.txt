Laravel Learning Project
=========================
This learning project doing in the env linux-mint 18 with php7.0

Installation process of laravel in php-7
=========================================
sudo apt-get install apache2-mod
sudo apt-get install php7
sudo apt-get install mysql-server
sudo apt-get install php7-mbstring
sudo apt-get install php7-xml

Getting laravel package using composer
=======================================
composer global require "laravel/installer"
composer create-project --prefer-dist laravel/laravel <project_name>