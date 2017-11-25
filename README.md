# Silverstripe PHP 5.6 requirements

- sudo add-apt-repository ppa:ondrej/php
- sudo apt-get install php5.6-xml
- sudo apt-get install php5.6-soap
- sudo apt-get install php5.6-xdebug
- sudo apt-get install php5.6-mbstring
- sudo apt-get install php5.6-mysql
- sudo apt-get install php5.6-tidy
- sudo apt-get install php5.6-curl
- sudo apt-get install php5.6-gd
- sudo apt-get install php5.6-intl
- sudo apt-get install php5.6-mcrypt


# Silverstripe PHP 7 requirements

- sudo add-apt-repository ppa:ondrej/php
- sudo apt-get install php7.0-intl
- sudo apt-get install php7.0-mbstring
- sudo apt-get install php7.0-xml
- sudo apt-get install php7.0-curl
- sudo apt-get install php7.0-gd
- sudo apt-get install php7.0-tidy

# Set timezone in php.ini
- date.timezone = 'Pacific/Auckland'

# Set silverstripe folder permissions
- sudo chown davidm:www-data . -R

# Enable mod rewrite
- sudo a2enmod rewrite

# SilverStripe .env file
- SS_DATABASE_CLASS="MySQLDatabase"
- SS_DATABASE_SERVER="localhost"
- SS_DATABASE_USERNAME="root"
- SS_DATABASE_PASSWORD="password"
- SS_DATABASE_CHOOSE_NAME="true"
- SS_ENVIRONMENT_TYPE="dev"
- SS_DEFAULT_ADMIN_USERNAME="admin"
- SS_DEFAULT_ADMIN_PASSWORD="password"



