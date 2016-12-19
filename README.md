# controlled_jenkins_update-center

WHAT
============
This is a static file version to control the http://updates.jenkins-ci.org/update-center.json and fix a release "personal stable" version. 

WHY
============
Because I (and all admin users) receive CONSTATLY the message "New version of Jenkins (2.xx) is available for download (changelog)." in my Jenkins instance and it´s annoying.
But why not just upgrading the instance? Because I have some custom plugin and I don´t have time to check compatibility.

HOW (usage)
============
OPTION1: Go to http://<jenkins_instance>/pluginManager/advanced > "Update Site" and replace the URL by the https://raw.githubusercontent.com/matiasburni/controlled_jenkins_update-center/master/update-center.json
If you want you can fork and edit the versions...

OPTION2: You can use the stable version https://updates.jenkins-ci.org/stable/update-center.json which is updated les frequently.

OPTION3: After Jenkins 2.x you can disable this notification on http://<jenkins_instance>/configure > Administrative monitors configuration > "Jenkins Update Notification"
