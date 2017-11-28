# Add the main PPA for PHP repository
- sudo add-apt-repository ppa:ondrej/php

# Silverstripe PHP 5.6 requirements

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

- sudo apt-get install php7.0-intl
- sudo apt-get install php7.0-mbstring
- sudo apt-get install php7.0-xml
- sudo apt-get install php7.0-curl
- sudo apt-get install php7.0-gd
- sudo apt-get install php7.0-tidy

# Silverstripe PHP 7.1 requirements

- sudo apt-get install php7.1-intl
- sudo apt-get install php7.1-mbstring
- sudo apt-get install php7.1-xml
- sudo apt-get install php7.1-curl
- sudo apt-get install php7.1-gd
- sudo apt-get install php7.1-tidy

# Switching PHP versions

## From php5.6 to php7.0:

### Apache
- sudo a2dismod php5.6
- sudo a2enmod php7.0
- sudo service apache2 restart
### CLI
- sudo update-alternatives --set php /usr/bin/php7.0

## From php7.0 to php5.6:

### Apache
- sudo a2dismod php7.0
- sudo a2enmod php5.6
- sudo service apache2 restart
### CLI
- sudo update-alternatives --set php /usr/bin/php5.6

# Set timezone in php.ini
- date.timezone = 'Pacific/Auckland'

# Set silverstripe folder permissions
- sudo chown davidm:www-data . -R

# Enabling mod rewrite
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
