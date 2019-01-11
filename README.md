# WordPress plugin unit tests

These files and folders for developers who want to run WordPress plugin unit tests on Windows but cannot install it using bash.

### To do:

All you have to do is download and extract everything in /tmp folder into your PHP CLI temp folder location and follow instructions on 3 README.md files.

Now, follow the **Generate the plugin test files** instruction on [thispage](https://make.wordpress.org/cli/handbook/plugin-unit-tests/).<br>
Don't forget to create your plugin PHP file with metadata otherwise it will be error and may have problem with PHP opcache (restart computer is needed if problem exists).

Run the <kbd>phpunit</kbd> command.

If no error occur then congratulations! You are ready to start plugin development.