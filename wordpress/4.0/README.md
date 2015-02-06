This is a tolerant Wordpress 4.0 rules set. Wordpress is a very complex system and it is possible that some parameters are missing in this rules set. If this is the case please submit the missing rules and/or manually add them to your system.


For security reasons you should ignore:

    [
        {"caller": "\/...\/wp-admin\/install.php", "path": "POST|admin_password"},
        {"caller": "\/...\/wp-admin\/install.php", "path": "POST|admin_password2"},
        {"caller": "\/...\/wp-admin\/options.php", "path": "POST|mailserver_pass"},
        {"caller": "\/...\/wp-admin\/profile.php", "path": "POST|pass1"},
        {"caller": "\/...\/wp-admin\/profile.php", "path": "POST|pass2"},
        {"caller": "\/...\/wp-admin\/user-new.php", "path": "POST|pass1"},
        {"caller": "\/...\/wp-admin\/user-new.php", "path": "POST|pass2"},
        {"caller": "\/...\/wp-admin\/user-edit.php", "path": "POST|pass1"},
        {"caller": "\/...\/wp-admin\/user-edit.php", "path": "POST|pass2"},
        {"caller": "\/...\/wp-admin\/user-new.php", "path": "POST|pass1"},
        {"caller": "\/...\/wp-admin\/user-new.php", "path": "POST|pass2"},
        {"caller": "\/...\/wp-login.php", "path": "POST|pass1"},
        {"caller": "\/...\/wp-login.php", "path": "POST|pass2"},
        {"caller": "\/...\/wp-login.php", "path": "POST|pwd"}
    ]

Do not forget to replace `...` with the location of your blog.
