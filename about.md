# OATS 1.0 - O'Neal's Aural Training Script
## Copyright
©2022 Utilars™ - https://www.utilars.com \
Utilars™ is a Faith based sole proprietorship of Shawn Eary

## License
To be Determined

OATS is a work in progress and legal details are still being sorted out. For the initial release, OATS will only be available through the Amazon App store. Source code is not available at this time.

## Purpose
The tool is primarily targeted at prospective undergraduate music majors that may struggle with beginning aural perception.

## Compatibility
### Devices
OATS was originally designed for a Best Buy OEM 32 inch Toshiba Fire TV, but it should work on most FireTV devices and some Fire Tablets. It is written in a manner that allows easy porting to other devices/platforms; however, only Amazon Fire echo devices are supported at this time.

### Input Controllers
An Amazon Fire remote and Rock Candy XBox compatible controler were both tested against the Toshiba Fire TV. Similar devices should also work. I was not able to test any other game controllers. While Amazon Fire remotes should work, it is unclear at this time if Amazon game controllers will work since the default game controller logic had to be overridden with Web Gamepad API to get XBox 360 compatible controllers to work. 

I do not currently own a tablet for testing, but should this app work on an Amazon Fire tablet (or touchscreen TV), the student can simply use finger presses to engage the user interface and no extra controllers will be needed.

## Attribution
### References
Below is an informal and temporarily list of references used while creating OATS. It's still needs to be cleaned up and formalized. OATS development was greatly speed up through the use of these resources.

https://answers.microsoft.com/en-us/xbox/forum/all/pausing-the-game-fallout4-with-xbox-controller/2de6f2df-6919-46a3-b8f7-ff9b524d5300\
https://api.jquery.com/html/\
https://developer.amazon.com/docs/fire-tv/supporting-controllers-in-web-apps.html\
https://developer.mozilla.org/en-US/docs/Web/API/BaseAudioContext/createGain#example\
https://developer.mozilla.org/en-US/docs/Web/API/Gamepad_API/Using_the_Gamepad_API\
https://developer.mozilla.org/en-US/docs/Web/API/OscillatorNode\
https://developer.mozilla.org/en-US/docs/Web/API/setInterval\
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/length\
https://englishstudyonline.org/words-that-start-with-s/\
https://en.wikipedia.org/wiki/Piano_key_frequencies\
https://github.com/chrisdavidmills/gamepad-buttons/blob/master/index.html\
https://github.com/kangax/html-minifier\
https://jqueryui.com/animate/\
https://jqueryui.com/effect/\
https://makefiletutorial.com/\
https://middleearmedia.com/web-audio-api-oscillators/\
https://modernweb.com/creating-sound-web-audio-api-oscillators/\
https://stackoverflow.com/questions/1103149/non-greedy-reluctant-regex-matching-in-sed\
https://stackoverflow.com/questions/26564825/what-is-the-meaning-of-a-double-dollar-sign-in-bash-makefile\
https://stackoverflow.com/questions/3276794/jquery-or-pure-js-simulate-enter-key-pressed-for-testing\
https://stackoverflow.com/questions/6449630/escaping-the-dollar-sign\
https://stackoverflow.com/questions/7316107/how-to-split-strings-over-multiple-lines-in-bash\
https://tecadmin.net/delete-a-line-containing-specific-string-using-sed/\
https://www.cyberciti.biz/faq/unix-linux-shell-removing-duplicate-lines/\
https://www.developer.amazon.com/docs/fire-tv/webapp-app-tester.html\
https://www.geeksforgeeks.org/javascript-removeeventlistener-method-with-examples/\
https://www.sitepoint.com/a-minimal-html-document-html5-edition/\
https://www.w3schools.com/jsref/jsref_concat_array.asp\
https://www.youtube.com/watch?v=E34H1ntipn0\
### Tool Chain
The following software was used in the development of OATS: 

Debian GNU\Linux 11 (Host OS for Dev Machine)\
Microsoft Visual Studio Code\
GNU Make and Standard GNU\Linux Commands such as Sed and zip\
Firefox and Google Chome (Research and App Testing)\
KDENLive (For Demo Video)\
Cubase 10.5 (Post Processing of Audio for Demo Video)

### Libraries/Dependencies
jQuery and jQueryUI
### Memorial
This app is dedicated to Curtis O'Neal Eary and Robbie Eary. Their love for their children will forever be remembered.
