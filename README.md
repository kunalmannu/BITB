# BITB ~
- Browser Templates For [Browser In The Browser (BITB) attack
- So Basically In (BITB) There Will Be A Fake Popup As It Requires A Permission To Give A Popup In The Normal Way So In The Fake Popup There Will Be A Iframe Of A Phishing Site.
- At The Start When The User Vist The Main Page Which Is The Main.html. The Main File Detects The User OS And Also Detects If The User Theme Is Dark Or Light And Redirects Them 
- To Their Required Web Pages. A Big Credit Goes To mrd0x As He Made The Project In Which I Did Some Big Changes Like Removing The Close Button So That The Victim Could Not 
- Close It, Adding The Main File, Some CSS Edits And Etc So That It Could A Lot Easier And Also Added Some Other OS's Like Kali-Linux and Ubuntu

# Installation
Just Download The Zip File From This Github Or Go To Your Terminal And Paste
- git clone https://github.com/kunalmannu/BITB.git

# Usage ~

Each folder has a `index.html` file which has 4 variables that must be modified:

* **XX-TITLE-XX** - The title that shows up for the page (e.g. Sign in to your account now)
* **XX-DOMAIN-NAME-XX** - Domain name you're masquerading as. (e.g. login.microsoft.com)
* **XX-DOMAIN-PATH-XX** - Domain path (e.g. /auth/microsoft/login)
* **XX-PHISHING-LINK-XX** - Phishing link which will be embedded into the iFrame (e.g. https://example.com)

Furthermore, If You're Using A Ubuntu Or Windows Template You Should Update The `logo.svg` Which Is The Icon Of The Website You're Masquerading As. The Default Logo Is Microsoft.

# Tested In ~
* **Kali Linux** ✅
* **Ubuntu** ❌ Lol I Dont Have Ubuntu So If You See Any Bugs In Ubuntu PLease Tell Me
* **MacOS Monterey 12** ✅
* **Windows 10** ✅
* **Windows 11** ✅


# Delay's ~
In The Delay's Folder Everyting Is Same But It Makes A Slight Delay To The Pop-up Window As It Appears. This Is Only One Way Of Making The Window Appear In A Delayed Fashion, There's Various Other Ways To Do The Same.

# Dragging the Window ~

One Way Of Detecting BITB Is By Attempting To Drag The Window To The Edge Of The Browser. If The Window Cannot Escape The Browser Then It's Not A Real Window. 

# Disclaimer ~

Usage Of These Templates For Attacking Targets Without Prior Consent Is Illegal. It's The End User's Responsibility To Obey All Applicable Laws. The Developer Is Not Responsible For Any Misuse Of These Templates.

# Images
![macdark](https://github.com/kunalmannu/BITB/assets/112188096/97dfddb5-a67e-45da-9002-9d4b14187503)


![maclight](https://github.com/kunalmannu/BITB/assets/112188096/d03127b8-c8c4-4011-8396-cf8c679237cb)

# Thank You
