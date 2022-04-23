# Customized Mozilla Firefox simulated-devices

I created this repository to add custom devices into the Simulated Devices file for Mozilla Firefox. If anything should happen to the Firefox, or device I am working on, I have a complete backup of the file.

I have no idea if there is a better or easier way to do this.
I cant see that I am the only one to ever think of this so I am sure there is custom lists available, but if you are interested, you are welcome to use this one.

## Requirements

I did not go and test every version of Mozilla Firefox. I can however tell you that Mozilla Firefox Developer Edition v92.0b9 (64-bit) and newer will work.
You can download the developer edition from [https://www.mozilla.org/en-US/firefox/developer/](https://www.mozilla.org/en-US/firefox/developer/).

## Setup / Installation

There is no installation as Firefox connects to a URL to get the devices file.
To set it up, Open up your Mozilla Firefox and type `about:config` in the navigation bar (the bar where you type the website url) and hit enter.
You will be prompted with a "Proceed with Caution" screen where you accept the rist and continue.
In the "Search preference name" bar type `devtools.devices.url` and hit enter.
It will be displayed below the search bar and to the right you should see an icon of a pen that you have to click. Once you clicked on the pen a new window will open where you can type your customized .json url. [https://raw.githubusercontent.com/stephane-klein/Firefox-Responsive-Devices/main/devices.json](https://raw.githubusercontent.com/stephane-klein/Firefox-Responsive-Devices/main/devices.json)

## SideNote

The custom devices list come from https://screensiz.es/ and [https://en.wikipedia.org/wiki/List_of_common_resolutions](https://en.wikipedia.org/wiki/List_of_common_resolutions) as a reference for devices and resolution sizes as it most accurately corresponds with the default list.

For the User Agent's I will use [https://developers.whatismybrowser.com/useragents/explore/operating_platform_string/?utm_source=whatismybrowsercom&utm_medium=internal&utm_campaign=breadcrumbs](https://developers.whatismybrowser.com/useragents/explore/operating_platform_string/?utm_source=whatismybrowsercom&utm_medium=internal&utm_campaign=breadcrumbs).
I am having some dificulty getting the correct ones but its a start.
