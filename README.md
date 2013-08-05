The purpose of this app is to test scrolling performance on various devices
against a Sencha Touch 2.2.1 built,
especially Android devices.

### Start Local Web Server

> sencha fs web -p 3001 start -map android/channelcandy=.


### Package the Project Native

> sencha app build -c -e native


### Build Project for Deployment

> sencha app build -c -e package


### Run App in Simulator

> sencha app build -c -r -e native
