# SBGetLink
This repository contains a deployable package for implementation of Deep Link in target environment.

# Deep Link
Deep link is a functionality that provides you with ability to get web link to a record in a form.
To turn on functionality:
1. Go to "User options" -> "Preferences"
![User options - preferences](https://raw.githubusercontent.com/SmartBusinessLLC/SBGetLink/SBSystemAdministrationCheckBox/Screenshot_10.png)
2. Check "Turn on deep link"
![Turn on deep link](https://raw.githubusercontent.com/SmartBusinessLLC/SBGetLink/SBSystemAdministrationCheckBox/Screenshot_11.png)

To use deep link you need:
1. Open form
2. Move cursor to a record you need a link to
![Choose Record](https://raw.githubusercontent.com/SmartBusinessLLC/SBGetLink/master/Screenshot_7.png)
3. Click "Get Link"
![Click Get Link](https://raw.githubusercontent.com/SmartBusinessLLC/SBGetLink/master/Screenshot_8.png)
4. Copy provided link and use it
![Use link](https://raw.githubusercontent.com/SmartBusinessLLC/SBGetLink/master/Screenshot_9.png)

# Apply to target environment

To use this functionality you need to download deployable package and deploy it to a target environment.

Instructions on how to apply deployable package to cloud-hosted environment: https://docs.microsoft.com/en-us/dynamics365/unified-operations/dev-itpro/deployment/apply-deployable-package-system

Instructions on how to install deployable package on development environment: https://docs.microsoft.com/en-us/dynamics365/unified-operations/dev-itpro/deployment/install-deployable-package

# Version information
This extension was tested for next Dynamics 365 for Finance and Operations version:

Installed product version : Microsoft Dynamics 365 for Finance and Operations, Enterprise edition (July 2017)

Installed platform version : Update11 (7.0.4679.35176)

# Changes added with this package

AXDeployablePackage_20180403_16_01_31: 
Changeset:
 - SBSysUserSetup_EventHandler class
 - SBGetLinkActive EDT
 - SysUserSetup.Extension_SB form extension
 - SBL_en-US label file
 - SysUserInfo.Extension_SB table extension
 
 With this version you are able to turn on and off the functionality of Deep Link from User options.
 
 ------------------------------------------------------------------------------------------------------------

AXDeployablePackage_20180402_16_50_50: This deployable package adds SBUrl_Extension class to your environment

# Source of information for this project

The source of information used to create this projects: https://thwidmer.wordpress.com/2017/11/02/deep-links-available-in-every-form/
