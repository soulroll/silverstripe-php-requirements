# Silverstripe PHP requirements
Just a list of things needed to get SilverStripe working on your local environment.

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

# php.ini
- date.timezone = 'Pacific/Auckland'
- always_populate_raw_post_data = -1

# SilverStripe .env file
- SS_DATABASE_CLASS="MySQLDatabase"
- SS_DATABASE_SERVER="localhost"
- SS_DATABASE_USERNAME="root"
- SS_DATABASE_PASSWORD="password"
- SS_DATABASE_CHOOSE_NAME="true"
- SS_ENVIRONMENT_TYPE="dev"
- SS_DEFAULT_ADMIN_USERNAME="admin"
- SS_DEFAULT_ADMIN_PASSWORD="password"
