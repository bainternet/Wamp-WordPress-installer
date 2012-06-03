# Simple WordPress Auto Installer for WAMP
![wamp wordpress installer](http://i.imgur.com/cvZZK.jpg)
## **Background**
Simple WordPress Auto Installer for [WAMP](http://www.wampserver.com/en/)(and Most other amp stacks like xampp....) is something that i coded after a friend of mine asked me if there is a fantastico installer for WAMP, which was funny since he only needed it to install WordPress. 

The i figured Installing WordPress is a very simple flow of 

- Downloading the latest version.
- Extracting the downloaded zip file.
- Creating a new database.
- Creating wp-config.php file.

And since I'm such a good friend :) and I myself install WordPress locally on WAMP a few time a day then i coded this really quick script that takes care of the flow above and has a few more features.


## Usage
Simply drop `installer.php` file in your www root directory and access it using your browser of choice.

Once you are there you will see something similar to the image above, fill in the required fields and click `GO`
the script will then download the latest copy of WordPress, extract the files to the directory you named and will create a new database (assuming that you have provided the needed information) and then will take you straight to where all you have to do is set you sites name, your username and pass and you have a new WordPress Installation ready to roll.

## License
Copyright 2012, Ohad Raz <admin@bainternet.info>

## Changelog:

0.2
- Changed logic for download.
- Added a few other laguages by requests.
- Chaged the UI a bit.
- Added auto database name based on folder.
- Added links for download and support.
- Fixed some html errors.


0.1
- Initial release

licensed under the GPL license: [http://www.gnu.org/licenses/gpl.html](http://www.gnu.org/licenses/gpl.html)
license.txt file included.