# tiborb.github.io

## Tagging guide with Tealium iQ
* This guide will cover the tag implementation including the data layer
* See more info on the data layer here: <link>

### 1. Website

* Make sure you have access to the source code of the page you want to implement the tracking code
* Add the Tealium Tag on to all pages, in most cases a 'master' template is the most suitable approach, this way the tags wil be loaded for all pageloads across your website or web application

### 2. Tealium Tag
##### Obtaining the default Tealium tag
* Make sure you have a user account in Tealium (for an account, please contact <xyz>)
* Follow the steps described here to obtain the correct tracking code and the plain data layer (utag_data):
https://community.tealiumiq.com/t5/iQ-Tag-Management/Code-Center/ta-p/13631
* Alternatively a responsable can create the tag for you, or follow the instructions written here: https://inside-docupedia.bosch.com/confluence/display/BDTECH/Technical+Implementation+of+utag.js#TechnicalImplementationofutag.js-OPTION1:UniversalDataObject

### 3. Additional Vendors
You will require a Tealium user account in order to enter the necessary Tag Settings

##### Webtrends
* The Webtrends Tag will be activated from the Tealium iQ GUI.
* An adapter between the default data layer and webtrends is available in the Bosch Tealium instance

##### Google Analytics
*

### 4. Customization
* After basic tag implementation has been completed, basic metrics can be tracked out of the box
* For more advanced questions, event tracking, interval search etc. some degree of customization might be required. This is heavily dependent on the page being tracked because the structure might be unique.

#### Populating the data layer
* See the supported DL variables here: https://deploytealium.com/verify/dataLayerRecommendation.php?account=robert-bosch&pin=59677c5107448&title=central-datalayer
* Note that DL schema TBD
####  Event Tracking
*
