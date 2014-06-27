Shifty Spritz
=============

Easy to use Javascript Spritz-type reader extension for Chrome and Firefox. To build and get a demo of the latest version of Shifty Spritz follow the build instructions for your prefered browser below. Please take note that the build instructions are only for Mac and Linux. Please feel free to contribute to the project as 2 brains are better than one.

### Chrome Build
Make sure you have [nodejs](http://nodejs.org/) and [grunt CLI](http://gruntjs.com/getting-started) installed before doing the commands below in terminal.

    git clone https://github.com/andrewmilson/shifty-spritz.git
    cd shifty-spritz/
    npm install
    cd chrome/
    grunt build

Then in Google Chrome head over to tools > extensions. Click the button at the top that says "Load unpacked extension". Locate the build directory inside shifty-spritz/chrome/ and press select. After that its just a matter of loading a webpage and doubble tapping the SHIFT key on some selected text and watching the magic appear in front of you.

### Firefox Build
Make sure you have [cfx](https://developer.mozilla.org/en-US/Add-ons/SDK/Tools/cfx) installed. Then open up terminal and follow the commands below.

    git clone https://github.com/andrewmilson/shifty-spritz.git
    cd shifty-spritz/firefox/

    # Launch an instance of Firefox with your Shifty Spritz installed.
    cfx run

    # ~ OR ~

    # Package Shifty Spritz as an XPI file, which is the install file format for Firefox add-ons.
    cfx xpi

If you chose `cfx xpi` and you want to install the extension in your browser open up firefox. In `Tools -> Add-ons` go to the settings dropdown and choose `Install Add-on from file`. choose the xip file that you just created. After that its just a matter of loading a webpage and doubble tapping the SHIFT key on some selected text and watching the magic appear in front of you.
