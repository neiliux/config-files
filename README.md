# config-files
A collection of various configuration files and scripts

### OSX/
* ###### promptShell
A (OSX) bash script to configure your prompt shell (PS1) to include SVN or GIT information on WD

I place this file in /etc and source it from /etc/bashrc via the below snippet; however, you can source this from other locations.

```
[ -r /etc/promptShell ] && . /etc/promptShell
```

* ###### hushlogin
Removes any login messages when terminal is opened (last login, etc.).
Copy this file to ~/.hushlogin

