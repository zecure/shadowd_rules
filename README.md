**Shadow Daemon** is a collection of tools to **detect**, **protocol** and **prevent** **attacks** on *web applications*. Technically speaking, Shadow Daemon is a **web application firewall** that intercepts requests and filters out malicious parameters. It is a modular system that separates web application, analysis and interface to increase security, flexibility and expandability.

This repository contains whitelist and blacklist rules. Feel free to submit your own rules or improvements.

# Conventions
Directory structure:

    appname/version

File structure:

    Blacklist: appname-version_b.txt
    Whitelist: appname-version_w.txt

The application names are written in lower case. Space and other special characters are replaced by underscores.
