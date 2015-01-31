My first app running on AWS
=============

Sample app besed on Nette framework.

[Nette](http://nette.org) is a popular tool for PHP web development.
It is designed to be the most usable and friendliest as possible. It focuses
on security and performance and is definitely one of the safest PHP frameworks.


Installing
---------- 

Install dependencies by running Composer install.

Make directories `temp` and `log` writable. Navigate your browser
to the `www` directory and you will see a welcome page.

It is CRITICAL that whole `app`, `log` and `temp` directories are NOT accessible
directly via a web browser! See [security warning](http://nette.org/security-warning).
