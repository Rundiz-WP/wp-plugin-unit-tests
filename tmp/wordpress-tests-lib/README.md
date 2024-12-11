# Tests config and functions

### Install:

Follow these instruction after you copied the files to temp location and may be run any command from there.

1. Open wp-tests-config.php file.
2. Change the database values.
3. Save changed.
4. Create the database with the same name in configuration. This database must be blank because it will be automatically **delete** everything.
5. Run `composer install` in the command line to install required package(s).

### Upgrade/Update:
You can update all the files in folder **data**, **includes** use following URLs.

* For **data** folder: **http://develop.svn.wordpress.org/tags/{WORDPRESS_VERSION}/tests/phpunit/data/**
* For **includes** folder: **http://develop.svn.wordpress.org/tags/{WORDPRESS_VERSION}/tests/phpunit/includes/**

#### Manual
Download all files and folders from the URLs above to this folder on your temp location.

Replace `{WORDPRESS_VERSION}` with your WordPress version (recommend latest). For example: `6.7.1`.  
#### Use SVN client
You may download use sub version client such as TortoiseSVN. Follow these instruction on target folder one by one.

For new check out:
1. Right click on this folder and click checkout.
2. Enter the URL above by replace `{WORDPRESS_VERSION}` to the version you want.
3. Click OK.

For upgrade:
1. Right click on working copy (**data**, and **includes**) and select 'Switch...'
2. Change WordPress version number to what you want. For example `6.7.1`.
3. Click OK.