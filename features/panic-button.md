# Wipe data

A Quick Delete button allows users, in a just a few seconds, to delete sensitive data within Tella. The button can also be set to delete the app itself.

A different version of Tella \(v1.5b\) includes a full-fledged Panic Button as a way to protect users from physical repression. Due to Google restrictions, this version of Tella is not available on the Google Play Store and must be downloaded directly [here](https://hzontal.org/tella). When users trigger the Panic Button, three actions take place:

1. An SMS is sent to a list of trusted contacts, which includes a custom message and the user's geolocation at the time. The list of trusted contacts and the message must be set ahead of time.
2. Data stored within Tella is deleted. The exact datasets to be deleted \(multimedia files, forms, Panic Button data, etc\) must be set ahead of time.
3. Tella itself is deleted. This requires the user to confirm the request to delete the app, which will pop-up on the screen immediately after the Panic Button is triggered.

**WARNING:** the Panic Button is not a foolproof protection tool. There are a number of things to keep in mind when using it or suggesting it to a group of users:

* Because it is only accessible from within Tella \(and because Tella needs to be unlocked every time it is opened\), it is not suitable for all emergency situations. Indeed, if the user is _not_ using Tella when faced with an immediate danger, it may take some time before they can trigger the Panic Button \(as it requires first opening the application, then unlocking it, and finally triggering the Panic Button\). Therefore, the Panic Button is more suitable as a protection tool when users are in the process of using Tella -- for example using the camera or filing a form.
* SMS is an extremely insecure form of communication: telecommunication agencies, governments and hackers can easily intercept messages and identify recipients. Users must be mindful of the risks involved with using SMS as a channel to send an alert.
* The SMS sent by the Panic Button remains stored in the device's default SMS app. This means that an individual seizing the device after the Panic Button was triggered may be able to see the Panic message and who it was sent to. This may endanger both the user and the recipients of the Panic SMS.

