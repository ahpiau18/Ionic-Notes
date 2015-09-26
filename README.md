# Ionic-Notes
This is to record the issues that i faces during development


Errors<BR>
<b>01.</b> when i type "ionic emulate ios", i got the error below : <BR>
    simctl was not found.<BR>
    Check that you have Xcode 6.x installed:<BR>
	    xcodebuild --versionCheck that you have Xcode 6.x selected: <BR>
	    xcode-select --print-path<BR>
	    <BR>
    Solution : open Terminal, type "npm update -g ios-sim"
    

<b>02.</b> image is not able to display while "ionic emulate ios", and my image is located at www\img\
    Solution : make sure the image src syntax is "./img/{imagename}" instead of "img/{imagename}"
