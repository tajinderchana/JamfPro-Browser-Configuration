# Custom Schema for JamfPro External Applications
Custom Schema that can be added into JamfPro to manage Google Chrome Settings across your environment. This will add settings that can be configured to manage settings in the browser.

## Getting Started
1. Create a new Configuration Profile

2. Name the profile and set following appropriate settings:
  - Name
  - Description
  - Catagory   
  - Distribution Method
  - Level
  
3. Set the scope for whos this profile will be applied to

4. Add the Application & Custom Settings payload and select External Applications and click Add
  -  **Source** - Custom Schema 
  - **Preference Domain** - com.google.chrome
  - **Custom Schema** - Paste in the Custom Schema
  
 5. Scroll down and find all the settings from the custom schema. From here you will need to select what settings you and your organisation would want applied to Google Chrome. 
 
 Once **Save** has been clcked this will be applied to all devices in scope.
 
 6. In Google Chrome navigate to **chrome://policy/**. Here you will find all the settings that have been applied to Google Chrome

## Prerequisites
Google Chrome needs to be installed on the endpoint. This can be done via a policy using this script. 

It would be recomended that auto updates are enabled for Google Chrome by running this script [Link](https://github.com/hjuutilainen/adminscripts/raw/master/chrome-enable-autoupdates.py)
