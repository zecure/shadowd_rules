This is a tolerant Wordpress 4.0 rules set.


For security reasons you should ignore:
```
POST|admin_password       /.../wp-admin/install.php
POST|admin_password2      /.../wp-admin/install.php
POST|mailserver_pass      /.../wp-admin/options.php
POST|pass1                /.../wp-admin/profile.php
POST|pass1                /.../wp-admin/user-new.php
POST|pass1                /.../wp-admin/user-edit.php
POST|pass2                /.../wp-admin/user-new.php
POST|pass1                /.../wp-login.php
```

Wordpress also uses Javascript to generate code. This code looks like an attack to Shadow Daemon, so it is best to completely ignore this parameters:
```
POST|content              /.../wp-admin/post.php
POST|html                 /.../wp-admin/admin-ajax.php
```
