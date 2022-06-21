# Welcome to the shit show

Figured it would be good to have a place where ITH's can look at and find information as the articles are out of date often.<br>
If you want to include anything inparticular message on here or the discord and I will add it. I will probably make this editable by certain people in the future as newer ITH's will have different or better ways to do things

## Yeet

This includes the most common things that I have <br> used on the job but it may not answer all of the questions you have. Google and Teams is still your best friend in this <br>

## Networking
If you have any networking issues this is probably the heading for you. 

### How to deal with eduroam issues<br>

Just to clear up, you can only use eduroam if you have a valid user account like staff or student username <br>
Some PhD students have weird ones but they should still work, visitors cannot use it and must use UOPGUEST instead

Toggle on and off the Wifi<br>
Forget the network<br>
Reboot the device<br>
Uninstall the network driver<br>
Run Win+r and type "winget upgrade --all" and run all of the updates<br>
Turn off anti-virus <br>
Ensure IP address and DNS settings are valid, ensure it is using DHCP and not static unless specified <br>
If the user knows that a recent update had occured and this led to the problem, see if you can roll back the update <br>
Ensure that no IPv6 addresses were configured <br>

If they are on an android, they must ensure that the following settings have been configured <br>

Open the device's Settings menu and select WiFi<br>
Select **Bold**eduroam**Bold** on the list of available networks<br>
Set EAP method to PEAP<br>
Set Phase-2 authentication to MSCHAPv2<br>
Select Do Not Validate<br>
Enter port.ac.uk in the Domain field (if required)<br>
Enter your student or staff network username (PC Login Username) in the Identify field (add @port.ac.uk as part of the name e.g up874068@port.ac.uk / smithj@port.ac.uk)<br>
In the Password field, enter your network password. Then select Connect at the bottom right of the screen<br>
eduroam will automatically connect every time you are within range of the wireless network<br>


If the user has come from another university, it is possible that the profile for the previous eduroam connection <br> causes issues. On a windows device we can try and perform a network reset. If on a Mac you will have to do the following <br> "sudo nano /Library/Preferences/SystemConfiguration/com.apple.network.eapolclient.configuration.plist". This should remove the old profile and then reboot the device. 

Try clearing the network settings from command prompt<br>

i. netsh winsock reset – reset back to default setting or clean state<br>
ii. ipconfig /release – force the client to give up its lease<br>
iii. ipconfig /renew –  renew/assign a new IP address<br>
iv. netsh int ip reset – reset TCP/IP back to its original configuration<br>
v. ipconfig /flushdns – clear the current cache of DNS records<br>

On some occassions it may be that the student is banned from using the wifi, typically due to torrenting on eduroam <br> 
This is not something that you can overturn, much rather something networks would do but this is unlikely as it is a <br> three strikes and your out system. This applies to both wired and wireless eduroam.

If all this fails then log a job to networks on service desk and be sure to include the MAC address of the device.<br>
If you don't it just draws out the wait time and leaves Networks having to get it from the student and if they don't <br>
know how then they will likely come back to the desk anyway so 


### How to deal with UOPGuest issues<br>

Select the network and it should take you to a captiveportal page where you enter in your details. These can be fake, such as "j" for the name and "j@g.com" for the email
If you get into a loop then try and enter the webpage address through firefox as that is the best bet and often worked. If you cannot do that then....

Good luck is all i can say at this point honestly

## Printing

### Papercut

### Uni Devices

### LFP




