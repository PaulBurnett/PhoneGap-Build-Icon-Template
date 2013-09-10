PhoneGap-Build-Icon-Template
============================

A Photoshop Generator file for PhoneGap Build Icons

1) Double-click the ‘Edit and Save’ Layer to edit the Smart Object and design your icon at 1024x1024.
2) If you would like rounded corners then Control-click on the Group mask ‘Rounded Corner Mask’ and select ‘Enable Vector Mask’.
3) Save your edits and close the Smart Object.
4) Save your Photoshop file and the icons will be automatically created.
5) If you make a change then just save again to re-publish the icons.


To add these icons to your PhoneGap Build project:
1) Copy the folder of generated icons to the root of your PhoneGap Build project.
2) Rename the folder 'icons'
3) Move the default icon 'icon.png' from the icons folder to the root level of the project.
4) Copy the text below to your config.xml file

<!-- Icons -->
<!-- Default - N.B. This icon must reside at the root level of your application folder. -->
<icon src="icon.png" />

<!-- iOS -->
<icon src="icons/ios_icon.png" gap:platform="ios" width="57" height="57" />
<icon src="icons/ios_icon-72.png" gap:platform="ios" width="72" height="72" />
<icon src="icons/ios_icon@2x.png" gap:platform="ios" width="114" height="114" />
<!-- retina iPad support: PhoneGap 2.5.0+ only -->
<icon src="icons/ios_icon-72@2x.png" gap:platform="ios" width="144" height="144" />

<!-- Android -->
<icon src="icons/ldpi.png" gap:platform="android" gap:density="ldpi" />
<icon src="icons/mdpi.png" gap:platform="android" gap:density="mdpi" />
<icon src="icons/hdpi.png" gap:platform="android" gap:density="hdpi" />
<icon src="icons/xhdpi.png" gap:platform="android" gap:density="xhdpi" />

<!-- BlackBerry -->
<icon src="icons/bb_icon.png" gap:platform="blackberry" />
<icon src="icons/bb_icon_hover.png" gap:platform="blackberry" gap:state="hover"/>

<!-- Windows Phone -->
<icon src="icons/winphone_icon.png" gap:platform="winphone" />
<icon src="icons/winphone_tileicon.png" gap:platform="winphone" gap:role="background" />

<!-- WebOS -->
<icon src="icons/webos_icon.png" gap:platform="webos" />
<icon src="icons/webos_miniicon.png" gap:platform="webos" gap:role="mini" />

