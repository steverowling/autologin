# Auto Login plugin for Craft CMS

Automatically login a front end user after they have successfully used the password reset functionality to set a new password.

![Screenshot](resources/screenshots/plugin_logo.png)

## Installation

To install Auto Login, follow these steps:

1. Download & unzip the file and place the `autologin` directory into your `craft/plugins` directory
2.  -OR- do a `git clone https://github.com/steverowling/autologin.git` directly into your `craft/plugins` folder.  You can then update it with `git pull`
3. Install plugin in the Craft Control Panel under Settings > Plugins
4. The plugin folder should be named `autologin` for Craft to see it.  GitHub recently started appending `-master` (the branch name) to the name of the folder for zip file downloads.

Auto Login works on Craft 2.4.x and Craft 2.5.x.

## Auto Login Overview

Automatically logs in a front end user when they have successfully reset their password after following the link in the Craft-generated password reset email.

Checks for a front end request and to make sure the user isn‘t already logged in first.

## Auto Login Changelog

### 1.0.0 -- 2016.04.10

* Initial release

### 1.0.1 -- 2016.04.23

* Add check for new user registration as Craft already provides a config setting to auto login on new user registration.

Brought to you by [Steve Rowling](https://springworks.co.uk)