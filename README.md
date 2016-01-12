![Logo](http://shadowd.zecure.org/img/logo_small.png)

**Shadow Daemon** is a collection of tools to **detect**, **record** and **prevent** **attacks** on *web applications*.
Technically speaking, Shadow Daemon is a **web application firewall** that intercepts requests and filters out malicious parameters.
It is a modular system that separates web application, analysis and interface to increase security, flexibility and expandability.

This repository contains whitelist, blacklist and integrity rules. Feel free to submit your own rules or improvements.

# Conventions

## Directory structure

The application names are written in lower case. Space and other special characters are replaced by underscores.

    appname/version

## File structure

The rules are in the following files:

    appname-version_blacklist.txt
    appname-version_whitelist.txt
    appname-version_integrity.txt

Sensitive user input that should be ignored is in this file:

    appname-version_ignore.txt

Please note that in some cases you will have to replace *...* in the ignore caller with the actual (json-encoded) path of that caller.

## Scope

The sets should not include rules for installation or update scripts that should not be accessible in a production environment.
