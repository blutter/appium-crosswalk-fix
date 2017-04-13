# Appium with Crosswalk Fixes

This repo contains changes to address Crosswalk webview issues inside Appium as described in 
https://github.com/appium/appium/issues/4597

To use:

    npm install https://github.com/blutter/appium-crosswalk-fix/archive/v1.6.4.tar.gz
    node_modules\appium-with-crosswalk-fix\node_modules\.bin\appium --chromedriver-executable=%cd%\node_modules\appium-with-crosswalk-fix\chromedriver\2.28\chromedriver.exe

or for OSX:

    ./node_modules/appium-with-crosswalk-fix/node_modules/.bin/appium --address 10.10.247.103 --port 4723 --session-override --chromedriver-executable=`pwd`/node_modules/appium-with-crosswalk-fix/chromedriver/2.27/osx/chromedriver
   
## Contents

This version of Appium referenced here uses a patched version of the appium-android-driver and a patched version of
chromedriver.

The chromedriver patch is from https://codereview.chromium.org/2375613002/
