# jenkinsDemo

##Access Needed
* GitHub Account (w/credentials)
* DockerHub Account (w/credentials)
* Running DC/OS Cluster (w/publicNode)

##Prerequisites
* Fork the “mesosphere/cd-demo” GitHub Repo using your account
* Deploy Jenkins in DC/OS (default settings)
* Deploy Marathon LB (default settings)
* Modify the “conf/cd-demo-app.conf” File

##Configure Jenkins
1. Input Account Credentials for GitHub and DockerHub
Build New “Freeform Project”
BUILD!

##Modify Application Deployment File
Modify the “conf/cd-demo-app.js” in the GitHub Repository that you forked for the demo.  The simplest way to do it is to navigate in the browser into the file, click the pencil (upper right) to edit, and the make the appropriate changes.  Don’t forget to “Commit Changes” (bottom) when you are done.  This can be done either before or during the demo based on desire, time, and confidence level.









