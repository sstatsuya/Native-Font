# Native-Font

<b>For Android. IOS I've not tested yet</b>


<li>Download then Extract</li>
<li>Copy all .ttf file to Project folder/assets/fonts</li>
<li>Create react-native.config.js in the root directory of your project then pasted this code</li>
<code>
module.exports = {
  assets: ['./assets/fonts'],
};
</code>
<li><code>cd .\android\</code> <code>.\gradlew clean</code></li>
<li>Run <code>npx react-native link</code></li>
<li>Restart App</li>
<li>Then use your font ex: fontFamily: 'font_name'</li>

<b><i>If Build Failed for Duplicate Resouce, you need to remove those file ttf because it conflict with vector icon library</b></i>
