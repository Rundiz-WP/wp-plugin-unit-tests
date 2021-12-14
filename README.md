## WordPress plugin unit tests

These files and folders for developers who want to run WordPress plugin unit tests on Windows but cannot install it using bash.

### Install:

* Download and extract everything inside **tmp** folder into your PHP CLI temp folder location.<br>
	For Windows, use this command to find out. `php -i | findstr temp`.<br>
	For Linux, use this command to find out. `php -i | grep temp`.
* Follow instructions on 3 **README.md** files.
* Follow the **Generate the plugin test files** instruction on [thispage][1]. Do not go to other step and no need to run bash. OR...
	* Download the [demo plugin test][3] from [this link][3].
* Create your plugin main file with [required header][2] to prevent error.
	* If the error occurs and it is related to PHP opcache, please restart your computer.
* Run `phpunit` command.

If no error occur then congratulations! You are ready to start plugin development.

### Notice

These files and folders are copied after I run the command on Windows sub system Ubuntu.<br>
All the credits are for these pages:

* https://make.wordpress.org/cli/handbook/plugin-unit-tests/ - WordPress official tutorial.
* https://www.chanhvuong.com/3368/install-subversion-on-ubuntu-wsl-on-windows-10/ Install SVN on Ubuntu.
* https://askubuntu.com/questions/223012/how-can-i-install-mysql-client-on-10-04 Install MySQL client on Ubuntu.

[1]: https://make.wordpress.org/cli/handbook/plugin-unit-tests/
[2]: https://developer.wordpress.org/plugins/plugin-basics/header-requirements/
[3]: https://github.com/Rundiz-WP/demo-plugin-test