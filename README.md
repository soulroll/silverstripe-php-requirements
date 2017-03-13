# silverstripe-php-requirements
Just a list of things needed to make SilverStripe work on your local enviroment

sudo apt-get install php5.6-xml
sudo apt-get install php5.6-soap
sudo apt-get install php5.6-xdebug
sudo apt-get install php5.6-mbstring
sudo apt-get install php5.6-mysql
sudo apt-get install php5.6-tidy
sudo apt-get install php5.6-curl
sudo apt-get install php5.6-gd
sudo apt-get install php5.6-intl

date.timezone = 'Pacific/Auckland'

New .env file
# DB credentials
SS_DATABASE_CLASS="MySQLDatabase"
SS_DATABASE_SERVER="localhost"
SS_DATABASE_USERNAME="root"
SS_DATABASE_PASSWORD="password"
SS_DATABASE_CHOOSE_NAME="true"
SS_ENVIRONMENT_TYPE="dev"
SS_DEFAULT_ADMIN_USERNAME="admin"
SS_DEFAULT_ADMIN_PASSWORD="password"
