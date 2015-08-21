Please remember that this sets are still **experimental**. There are a lot of special pages, so it is possible that in some rare cases rules are missing.


You should ignore these inputs:

    [
        {"caller": "\/...\/load.php", "path": "GET|*"},
        {"caller": "\/...\/index.php", "path": "POST|wpPassword"},
        {"caller": "\/...\/index.php", "path": "POST|wpNewPassword"},
        {"caller": "\/...\/index.php", "path": "POST|wpRetype"}
    ]

Do not forget to replace `...` with the location of your wiki.

The first entry is not a wildcard. There is an empty parameter with the name *asterisk*.
