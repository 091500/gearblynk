## GearBlynk - standalone app and widget for Samsung smartwatch series

Imagine you could control any of your Blynk running device from your wrist.
Now it is possible with GearBlynk app!

2018.08.07: GearBlynk is available for free download in Samsung Galaxy Apps store    
2018.11.28: GearBlynk PRO is available in Samsung Galaxy Apps store


**PRO version features:**

* Galaxy Watch support
* Custom Server support
* Color picker for widget slots
* 6 widget slots
* Usability improvements


Watch [video demo](https://www.youtube.com/watch?v=MkBfo__P5-Q) for GearBlynk Free version   
Watch [video demo](https://www.youtube.com/watch?v=i7XN_Xcg_Qs) for GearBlynk PRO version

Read [discussion thread](https://community.blynk.cc/t/gearblynk-standalone-app-and-widget-for-samsung-gear-s3-smartwatch-series/27725) on Blynk Community [Free version]  
Read [discussion thread](https://community.blynk.cc/t/gearblynk-pro-standalone-app-and-widget-for-samsung-smartwatch-series/30982) on Blynk Community [PRO version]  


### Requirements
1. [obtain](http://docs.blynk.cc/#getting-started-getting-started-with-the-blynk-app-4-auth-token) Blynk Auth token
1. make a Blynk project, use obtained token
1. install GearBlynk app from Samsung Galaxy Apps Store on your smartwatch and setup it


### App menu and configuration
App main menu consists of the following items:

➊ **Send Triggers** - send Triggers to your Blynk-running devices.

➋ **Setup Tokens** - add or delete your blynk Tokens (this will not delete token from your Blynk project).
Required fields: 
- Name
- Token

➌ **Setup Triggers** - add or delete your Triggers.
Required fields: 
- Name
- Token
- Pin type
- Pin number
- Pin Value
- Widget Slot

➍ **Setup Server** - setup server type. This option is available in **PRO version only**.
Required fields: 
- Server Type
- Server URL

When Server Type is 'blynk-cloud' then Server URL does not make any sense and could be not specified.
Server URL should be provided in format ip_address:port example:   
192.168.100.9:8080

➎ **Setup Widget** - assign Triggers to Widget slots.

➏ **Widget Colors** - assign colors to Widget slots. This option is available in **PRO version only**.

   
   
### App widget
Free version has a built-in Widget with **four** slots: top, bottom, left, right.
PRO version has a built-in Widget with **six** slots: 12h, 2h, 4h, 6h, 8h, 10h.
Custom Trigger could be assigned to each slot.

   
   
### Import Token feature (PRO version only)
This outstanding feature allows to quickly import long Blynk token strings instead of typing them on your watch!    
Make sure your watch is connected to internet. Then perform the following steps:    
1. visit [GearBlynk PRO Import Token service](https://thawing-savannah-47017.herokuapp.com)
2. generate short 4-symbol code for your Blynk token   
3. open GearBlynk PRO app and go to Setup Tokens -> Add -> Import Token   
4. enter generated 4-symbol code and enjoy   

In case something goes wrong you will see an error message.

### Network connection
GearBlynk app uses network connection only to send requests when you press widget slot 
buttons or choose an item from Send Triggers list.

Send Triggers menu item shows a notification if network connection is absent on your device.

You are able to use GearBlynk app even without WiFi connection. In this case your smartwatch should be connected to your phone over bluetooth. 
Bluetooth internet tethering should be enabled in your phone Connection Settings.

Bluetooth tethering on Android [setup](https://drive.google.com/file/d/1hOui7izz4d4lcZPP9c_yMw5HaqX0_ncA/view?usp=sharing)

Share your impressions with #GearBlynk hashtag

Thank you

### Free version History
2018.08.07 Free version release :fire:   
2018.08.20 Downloads from 68 unique countries from all over the world!  :open_mouth:        
2018.10.07 Downloads from 122 unique countries from all over the world! :clap:  
2018.11.30 Downloads from 134 unique countries from all over the world! :clap::clap:  


### PRO version History
2018.11.28 PRO version release :sunglasses:    
2018.12.21 Added custom server support  
2019.01.03 Added Import Token feature
