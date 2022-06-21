# Welcome to the shit show

Figured it would be good to have a place where ITH's can look at and find information as the articles are out of date often<br>
If you want to include anything inparticular message on here or the discord and I will add it. I will probably make this editable by certain people in the future as newer ITH's will have different or better ways to do things

### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for


### How to deal with Wifi issues<br>
Toggle on and off the Wifi<br>
Forget the network<br>
Reboot the device<br>
Uninstall the network driver<br>
Run Win+r and type "winget upgrade --all" and run all of the updates<br>
Turn off anti-virus <br>
Ensure IP address and DNS settings are valid, ensure it is using DHCP and not static unless specified <br>
If the user knows that a recent update had occured and this led to the problem, see if you can roll back the update <br>
Ensure that no IPv6 addresses were configured <br>

If the user has come from another university, it is possible that the profile for the previous eduroam connection <br> causes issues. On a windows device we can try and perform a network reset. If on a Mac you will have to do the following <br> "sudo nano /Library/Preferences/SystemConfiguration/com.apple.network.eapolclient.configuration.plist". This should remove the old profile and then reboot the device. 

Try clearing the network settings from command prompt<br>

i. netsh winsock reset – reset back to default setting or clean state<br>
ii. ipconfig /release – force the client to give up its lease<br>
iii. ipconfig /renew –  renew/assign a new IP address<br>
iv. netsh int ip reset – reset TCP/IP back to its original configuration<br>
v. ipconfig /flushdns – clear the current cache of DNS records<br>


If all this fails then log a job to networks on service desk and be sure to include the MAC address of the device.<br>
If you don't it just draws out the wait time and leaves Networks having to get it from the student and if they don't <br>
know how then they will likely come back to the desk anyway so 

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [Basic writing and formatting syntax](https://docs.github.com/en/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/MaximusXVIII/ITHKnowledge.io/settings/pages). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://support.github.com/contact) and we’ll help you sort it out.
