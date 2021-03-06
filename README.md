# hubot-jenkins-notifier

[![Build Status](https://travis-ci.org/halkeye/hubot-jenkins-notifier.png?branch=master)](https://travis-ci.org/halkeye/hubot-jenkins-notifier)
[![Dependency Status](https://gemnasium.com/halkeye/hubot-jenkins-notifier.png)](https://gemnasium.com/halkeye/hubot-jenkins-notifier)

Notifies about Jenkins build errors via [Jenkins Notification Plugin](https://wiki.jenkins-ci.org/display/JENKINS/Notification+Plugin)

## Getting Started
1. Install the module: `npm install --save hubot-jenkins-notifier`
2. Add it `hubot-jenkins-notifier` to your external-scripts.json file in your hubot directory
3. Add hubot's endpoint to jenkins jobs `http://<hubot-host>:<hubot-port>/hubot/jenkins-notify?room=<room>` (see Screenshot)


### Screenshot
![Jenkins Notifier Plugin Config Screenshot](jenkins-notifier-screenshot.png)



## Configuration
_(Coming soon)_

## Release History

0.1.4 - 2014-02-23

* Brought in recent changes from [github/hubot-scripts](http://www.github.com/github/hubot-scripts)
* Upgraded json parsing to handle/fail gracefully
* Handle jenkins not providing full url (for now not handled well, but better than undefined)
* Added screenshots to configuration

0.1.3 - 2013-08-05

* support hubot-irc adapter

0.1.2 - 2013-07-23

* allow `always_notify=1` cgi parameter to always notify a room even on success

0.1.1 - 2013-07-22

* Fixed up .npmignore file so the proper files were being packaged up

0.1.0 - Initial Release - 2013-07-20

* Based heavily on the [github/hubot-scripts](http://www.github.com/github/hubot-scripts) version which broke in our infrastructure

## License
Copyright (c) 2013 Gavin Mogan
Licensed under the MIT license.


[![Bitdeli Badge](https://d2weczhvl823v0.cloudfront.net/halkeye/hubot-jenkins-notifier/trend.png)](https://bitdeli.com/free "Bitdeli Badge")

