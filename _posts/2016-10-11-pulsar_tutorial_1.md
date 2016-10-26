Registering a Device for Use on the Wind River Helix App Cloud
To use the Helix App Cloud with Pulsar Linux, you must create an account and register your hardware device.
Prerequisites
You have a supported device with Pulsar Linux installed.
You have a Wind River customer support account.
Your device is running with console access.
You have another device with Internet access and a Web browser for accessing the Wind River Helix App Cloud website.
The steps in this procedure will prepare you for application development with the Helix App Cloud.
Procedure
Verify or create a Helix App Cloud account.
In a Web browser, navigate to https://app.cloud.windriver.com/.
Click Sign in with Wind River Account and enter your account credentials.
Register your Pulsar Linux hardware device.
Run the following command on your Pulsar Linux device to begin the registration process and create a registration key.
# registerTarget -n targetName
In this example:
the -n option indicates a new registration
the targetName is a name that you specify to recognize your device
Once the command completes, it provides information concerning the registration status, for example:
# registerTarget -n MyComputeStick-v2
Created target [ computestick ] on server [ app.cloud.windriver.com ]
Device registration status: pending
Device registration expires in 19.9666666666667 (mins)
Device Registration Key: 20d98
At the end of the output, the system provides a device registration key. In this example, the key is 20d98. Record this key, as it is required to register your device for use on the Helix App Cloud.
Register your device on the Helix App Cloud website.
Log in to your account at https://app.cloud.windriver.com/.
Click New Device in the upper right-hand corner.
When prompted, click Register an existing device using its Registration ID.
Enter the Registration ID (key) obtained in step 2, and a device name, then click Register Device.
Once the registration completes, a page will display with your device information and development options. You are now ready to use the Helix App Cloud.
Optionally create a new application project by clicking Create New Project. ../../img/icons/note.gif
NOTE: Information on developing applications with the Helix App Cloud is available on the website.