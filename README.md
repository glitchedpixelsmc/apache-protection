# apache-protection
These files WILL protect you from freaky stuff out there on apache.
###Installation
Clone to repo

`git init`

`git remote add protectmeplease git@github.com:glitchedpixelsmc/apache-protection.git:..git`

`git pull protectmeplease master`

Step 2:

Step 3:
add the following to all your files near the top
```php
<?php include(realpath(getenv('DOCUMENT_ROOT')) .'/blackhole/blackhole.php'); ?>
```
add the following to all pages near the bottom
