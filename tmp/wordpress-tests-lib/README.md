# Tests config and functions

### Install:

Follow these instruction after you copied the files to temp location and may be run any command from there.

1. Open wp-tests-config.php file.
2. Change the database values.
3. Save changed.
4. Create the database with the same name in configuration. This database must be blank because it will be automatically **delete** everything.
5. Run `composer install` in the command line to install required package(s).

### Upgrade/Update:

#### Manual
To update newer version of **includes**. Try to download files and folders from **http://develop.svn.wordpress.org/tags/{WORDPRESS_VERSION}/tests/phpunit/includes/**.  
To update newer version of **data**. Try to download files and folders from **http://develop.svn.wordpress.org/tags/{WORDPRESS_VERSION}/tests/phpunit/data/**.

Replace `{WORDPRESS_VERSION}` with your WordPress version (recommend latest). For example: `6.7.1`.  
#### Use SVN client
You may download use sub version client such as TortoiseSVN. Follow these instruction on target folder one by one.

1. Right click on working copy (**includes**, and **data**) and select 'Switch...'
2. Change WordPress version number to what you want. For example `6.7.1`.
3. Click OK.