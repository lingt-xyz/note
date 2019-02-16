---
title:  How to avoid using sudo when working in /var/www/html
layout: post
categories: linux
tags: linux

---

<!--more-->
Create a symlink for each project to your home directory. Say your project is located at `~/Projects/foo` and you want to have it located at `/var/www/html/foo`, run:
<!--more-->
```
sudo ln -sT ~/Projects/foo /var/www/html/foo
```
If your home directory has no execute bit (descend) set for other (for security reasons), change the group of it to www-data, but set the execute bit only (no read/write). Do the same for the `~/Projects` folder as it may contain other Projects than www. (You don't need `sudo` if you have previously added your user to the `www-data` group.)

```
sudo chgrp www-data ~ ~/Projects
chmod 710 ~ ~/Projects
```
Set the group to `www-data` on `~/Projects/foo` and allow the webserver to read and write to files and files+directories and descend into directories:
```
sudo chgrp www-data ~/Projects/foo
find ~/Projects/foo -type f -exec chmod 660 {} \;
find ~/Projects/foo -type d -exec chmod 2770 {} \;
```
Even safer: use 640 and 2750 by default and manually chmod files and directories that need to be writable by the webserver user. The setgid bit should be added only if you want every newly created file in `~/Projects/foo` to be accessible by the group.

From now on, you can access your site at `http://localhost/foo` and edit your project files in `~/Projects/foo`.

[How to avoid using sudo when working in /var/www/html](https://askubuntu.com/questions/46331/how-to-avoid-using-sudo-when-working-in-var-www/)