# Prototype WP

## Installation

`git clone https://github.com/jcsibon/prototype-wp`
`cd prototype-wp`
`wp core download --locale=fr_FR`
`wp core config --dbname='DBNAME' --dbuser='DBUSER' --dbprefix='DBPREFIX' --dbpass='DBPASS'`
`wp core install --url='URL' --title='TITLE' --admin_user='ADMIN_USER' --admin_password='ADMIN_PASSWORD' --admin_email='ADMIN_EMAIL'`
`wp rewrite structure '/%postname%'`