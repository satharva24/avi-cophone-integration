# avi-cophone-integration

AVI and Cophone Integration Repo

Cophone instance  - https://cophone.io/s/Michael_VMware_xk26v

Steps to install and deploy the application on cophone

* Install android studio (https://developer.android.com/studio)
* Clone this repository and open dalvik_app in android studio
* In android studio, go under build and Build App Bundle/APK and then Build APK
* On terminal run the cophone script with the -f flag (path to the apk)
*   python3 avi-dev/cophone_automation.py -b Dalvik -t {token_url} -o {open_website url} -i {install_apk url} -f /home/aviuser/app-debug.apk --verbose
* This will just install the apk on cophone. You can run it manually from the cophone instance or from the cophone script.

