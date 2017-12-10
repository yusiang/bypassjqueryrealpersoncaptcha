# BJRPC
A Chrome Extension written as a proof of concept to bypass jQuery Real Person Captcha (tested with version 2.0.1).

The plugin is configured by default to run on all pages. If it detects the jQuery Real Person Captcha it will attempt to parse the captcha content and fill in the captcha answer field with the captcha value.  

<h2>To install:</h2>

1. Save plugin folder to your desktop. 
2. In Chrome, click Menu > More Tools > Extensions. 
3. Click the "Load unpacked extension..." button. 
4. Select the saved plugin directory. 

<h2>To test:</h2>

To test the plugin, you can navigate to the Real Person Captcha homepage:
http://keith-wood.name/realPerson.html

or to the basic Real Person Captcha page:
http://keith-wood.name/realPersonBasics.html

<h2>To do:</h2>
1. Add functionality to work for different length captchas.<br/>
2. Add functionality to parse for numbers.<br/>
3. Add functionality to parse for other types of dots.<br/>
