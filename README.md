# apache-protection
These files WILL protect you from freaky stuff out there on apache.
###Installation
Clone to repo

`git init`

`git remote add protectmeplease git@github.com:glitchedpixelsmc/apache-protection.git:..git`

`git pull protectmeplease master`

Step 2:
Go to index.php (line 52): Set specific timezone
Step 3:
add the following to all your files near the top
```php
<?php include(realpath(getenv('DOCUMENT_ROOT')) .'/blackhole/blackhole.php'); ?>
```
add the following to all pages near the bottom
```html
<a rel="nofollow" style="display:none;" href="http://example.com/blackhole/">Do NOT follow this link or you will be banned from the site!</a>
```
