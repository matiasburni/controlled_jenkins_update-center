# controlled_jenkins_update-center

WHAT
============
This is a static file version to control the http://mirrors.seville-jam.es/jenkins/updates/current/update-center.json and fix a release "personal stable" version. 

WHY
============
Because I (and all admin users) receive CONSTATLY the message "New version of Jenkins (2.xx) is available for download (changelog)." in my jenkins instance and it´s annoying.
But why not just upgrading the instance? Because I have some custom plugin and I don´t have time to check compatbility.

HOW (usage)
============
Go to http://<jenkins_instance>/pluginManager/advanced > "Update Site" and replace the URL by the https://github.com/matiasburni/controlled_jenkins_update-center/blob/master/update-center.json

If you want you can fork and edit the versions...
