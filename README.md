# HelloPlugin7
1. This is just a small sample project to show the communication between WebView and Android native through Cordova.
2. The user can input two numbers through the WebView and she will be able to see the summation of two input numbers calculated at Android native.
3. How to run :
     a. Set up all the Cordova and Android stuff. (Please look at other references for this.)
     b. Do get this source. (ex. git clone https://github.com/hyoungtaikkim/HelloPlugin7.git)
     c. At command window, type in "cordova create myTest"
                                   "cd myTest"
                                   "cordova platform add android"
                                   "cordova plugin add ../HelloPlugin7/CordovaCustomPlugin"
                                   "cp -r ../HelloPlugin7/www ."
                                   "cordova build android"
                                   "cordova run android" (after running any Android emulator)
                                   
      
