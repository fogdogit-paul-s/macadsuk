###### Ben Toms dataJAR Ltd

### Key Takeaways:
- Plan for your fleet to be on macOS 14 by January 2024
- Investigate Lockdown mode
- they aren't patching all known security vulnerabilities in previous macOS versions
- hard to know via MDM if device on RSR (can use command below to display in terminal)
	- ``` echo "$(/usr/bin/sw_vers -productVersion) $(/usr/bin/sw_vers --productVersionExtra)"```
- Full slides and all links: [GitHub - dataJAR/macaduk2023: Repo for links from the macad.uk 2023 talk "What's new with Ventura for Mac admins"](https://github.com/dataJAR/macaduk2023) 


### Slides:
[Apple Platform Deployment – Apple Support (UK)](https://support.apple.com/en-gb/guide/deployment/welcome/web) 
![[image 9.jpg]]

[Apple Platform Deployment – Now available in a locale near you! – macmule](https://macmule.com/2022/11/08/apple-platform-deployment-now-available-in-a-locale-near-you/) 
![[image 10.jpg]]


[About software updates for Apple devices – Apple Support (UK)](https://support.apple.com/guide/deployment/depc4c80847a/1/web/1.0)

![[image 11.jpg]]



![[image 12.jpg]] 

**Lockdown Mode**
Check out Apple website for info 

Login Items 
[Example MDM profile for disabling BTM notifications · GitHub](https://gist.github.com/n8felton/f0530dd54e17b59cfe6710c853dcc8a1)
![[image 13.jpg]]

Declarative device mgmt - device informs MDM 

Managed device attestation

![[image 14.jpg]]
