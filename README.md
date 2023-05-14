## HoneyPi
HoneyPi: How to Create a Honeypot Server using Raspberry Pi and DShield
HoneyPi is a honeypot server built using Raspberry Pi and DShield to protect your network.

## Steps to Recreate:

1. Download and install the Raspberry Pi Imager software from https://www.raspberrypi.com/software/.

2. Insert an SD card into your computer's memory card reader.

3. Open the Raspberry Pi Imager software and select an operating system to install on the SD card.

4. Insert the SD card into your Raspberry Pi and power on the device.

5. Connect to your Raspberry Pi using SSH: ssh pi@raspberrypi.

6. Update your Raspberry Pi's software: sudo apt update && sudo apt-get -uy dist-upgrade.

7. Reboot the Raspberry Pi: sudo reboot.

8. Reconnect to the Raspberry Pi using SSH: ssh pi@raspberrypi.

9. Install Git: sudo apt-get -y install git.

10. Download the DShield Honeypot: git clone https://github.com/DShield-ISC/dshield.

11. Change to the honeypot directory: cd dshield/bin/.

12. Install the DShield Honeypot and follow the prompts: sudo ./install.sh.

13. Create an account on the DShield website and obtain an API key from https://isc.sans.edu/honeypot.html.

Once the installation is complete, expose your Raspberry Pi honeypot to the Internet and monitor your dashboard as logs are sent and usaually it gets update in about 30 minutes of the activity.
By following these steps, you can create a HoneyPi honeypot server to help protect your network.





