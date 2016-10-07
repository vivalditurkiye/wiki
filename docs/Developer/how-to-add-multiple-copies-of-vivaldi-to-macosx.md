## How to Add Multiple Copies of Vivaldi to Mac OSX

By default all copies of Vivaldi for OSX store their preferences (profile/settings) in the same location, which can make things tricky should you want to pre-test a snapshot before updating, or if you need to run the last beta alongside a snapshot build.

On Windows these issues can be overcome via the performing a "Standalone install" for builds you want to test. You might not be aware that it is also possible to do this on OSX as well. Rather than executing Vivaldi directly, you will need to create a launcher application that controls where Vivaldi stores its preferences. To do so, start **Terminal** and issue the commands below —just paste them  and press Enter.


	mkdir -p Standalone\ Mode.app/Contents/MacOS
	printf '#!/bin/sh\nopen -a "${0%%/*.app/*}"/[!\(Standalone\)]*.app --args --user-data-dir="${0%%/*.app/*}/profile"\n' > Standalone\ Mode.app/Contents/MacOS/Standalone\ Mode
	chmod +x Standalone\ Mode.app/Contents/MacOS/Standalone\ Mode

You should now have an application called "Standalone Mode", stored in the folder where Terminal is running—you can check the folder location with **pwd** or open the folder in Finder with "**open**".


* To make use of your newly created launcher move "Standalone Mode" and the version of "Vivaldi" you wish to run into an empty folder. Your browser should then be started by double clicking on "Standalone Mode", rather than Vivaldi directly. When started in this way, your preferences will then be stored in a sub folder called "profile", instead of the default directory.

* By moving the folder containing "**Standalone Mode**" and "Vivaldi" to a (HFS+ formatted) USB disk, you can even have a portable ("USB install") of Vivaldi, for sharing between multiple computers.

For those Mac users who feel comfortable and enjoy using the Terminal on a regular basis, I provide a script on GitHub that automates mounting a Vivaldi package, then extracting it to an appropriately version named directory and finally configuring a launcher.

Source: [Ruario / Vivaldi.Net](https://vivaldi.net/en-US/teamblog/78-running-multiple-copies-of-vivaldi-on-osx)
