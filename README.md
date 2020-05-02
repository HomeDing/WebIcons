# WebIcons for HomDing based devices

<style>
img { width:120px; background-color:silver}
</style>

Devices based on the HomeDing library are configured by using the Web UI interface.

Browsers will automatically search for the icons that are hosted on the device
that will be displayed in address bar and is used as the icon for favorites.

The standard Web UI uses the following standard symbol:

![HomeDing Device icon](/i/default.svg)

This can be exchanged by copying the favicons from one of the icon folders from this repository
into the root folder of the file system of the device.

* /favicons/<name>/*.png
* /favicons/<name>/*.svg


## Copy icons manually

1. Check-out or download this repository
2. open the Micro-IDE <http://homeding/microide.htm> or the built-in Upload tool <http://homeding/$upload.htm>.
3. drop the files from on of the folders to the device upload area.


## Copy icons using the icon update tool

t.b.d.


## Create favicons sets for the HomeDing library

When a new icon is available the makeicon script can be used to generate a new set of favicons.

>     node makeicon.js -n <name> -s

To generate all know icons the following command lin e can be used:

>     npm run makeall


## Remarks

The script depends on some deprecated libraries but still works on windows.

