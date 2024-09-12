# Captive Portal Auto-Detection Configurations

In this repository, I have compiled a collection of basic files that are used by operating systems and web browsers to detect the presence of a captive portal on a network.

These files are functional as provided; simply add them to your web server (e.g., Apache2 or Nginx). You can place your web server's source code inside the ```CaptivePortal``` directory, and the browser will automatically redirect to it. However, this alone will not work; you will still need to do some network configuration for it to function correctly.

Feel free to fork this repository and contribute additional files.

## How to use

1. Download it from [here](https://github.com/tt3rror/Captive-Portal-Auto-Detection-Configurations/archive/refs/heads/main.zip) or clone it.


		git clone https://github.com/tt3rror/Captive-Portal-Auto-Detection-Configurations.git

2. Go copy everything from the ```Webserver``` folder.

3. Paste them inside your Apache2 or nginx server.

4. Add your website inside the ```CaptivePortal``` folder.


## Additional Information Regarding the Configuration Files

Firefox

	http://detectportal.firefox.com/success.txt
	
	http://www.mozilla.org/firefox/captive-portal-success.html


Chrome:

	http://www.google.com/generate_204

	https://www.gstatic.com/generate_204

Windows:

	http://www.msftconnecttest.com/connecttest.txt


MacOs:

	http://captive.apple.com/hotspot-detect.html

	http://www.apple.com/library/test/success.html


Ubuntu:

	http://connectivity-check.ubuntu.com/


Android:

	http://connectivitycheck.gstatic.com/generate_204
	
	https://www.google.com/generate_204
