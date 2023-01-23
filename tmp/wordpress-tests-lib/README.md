# Tests config and functions

### Install:

1. Open wp-tests-config.php file.
2. Change the database values.
3. Save changed.
4. Create the database with the same name in configuration. This database must be blank because it will be automatically **delete** everything.
5. Run `composer install` in the command line to install required package(s).

### Upgrade/Update:

To update to support newer version of **includes**. Try to download files and folders from **http://develop.svn.wordpress.org/tags/{WORDPRESS_VERSION}/tests/phpunit/includes/**.  
Replace `{WORDPRESS_VERSION}` with your WordPress version (recommend latest). For example: `6.1.1`.
