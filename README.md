# Native-Font

<b>For Android</b>
<li>Download then Extract</li>
<li>Copy all .ttf file to Project folder/assets/fonts</li>
<li>Create react-native.config.js in the root directory of your project then pasted this code</li>
<code>
module.exports = {
  assets: ['./assets/fonts/', './assets/vector-icon-fonts/'],
};
</code>
<li>Restart App</li>
<li>Then use your font ex: fontFamily: 'font_name'</li>
