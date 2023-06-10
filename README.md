## CMDBuild_Persian
This is a patch for CMDBuild that improves functionality, specifically targeting Persian speakers who utilize the right-to-left script and follow the Persian(Jalali) calendar. CMDBuild is an open source web environment for the configuration of custom applications for Asset Management according to the needs of Organizations. The purpose of this patch is to enhance the user experience and inclusivity for Persian-speaking users, ensuring they can fully utilize cmdbuild while adhering to their linguistic requirements.

This is an unofficial repository.  
Official Maintainer: Tecnoteca - https://www.tecnoteca.com

![cmdbuild_logo](https://www.tecnoteca.com/immagini/logo_cmdbuild.png/@@images/bf2e13f9-7a90-4e41-ba76-cf8fe5a87d50.png)  
[CMDBuild](http://www.cmdbuild.org/en) is a web environment in which you can configure custom solutions for IT Governance, or more generally for asset management.  

[READY2USE](http://www.cmdbuild.org/en/prodotti/ready2use) pre-configured CMDBuild READY TO BE USED within the production environment  

[openMaint](http://www.openmaint.org) open source solution for the Property & Facility Management; an application for the management of buildings, installations, movable assets and related maintenance activities  

## LICENSE
This program is free software: you can redistribute it and/or modify
it under the terms of the GNU Affero General Public License version 3
as published by the Free Software Foundation.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.
See the GNU Affero General Public License for more details.

You should have received a copy of the GNU Affero General Public License 
along with this program.
If not, see <http://www.gnu.org/licenses/agpl.html>.
    
## How it works
1- Download and deploy CMDBuild 3.3 from official website 

2- Download "cmdbuild-3.3-fa-patch.rar" and extract it

3- Stop Tomcat

5- Replace "ui" folder entirely

6- Copy 3 jar files to "tomcat-home/webapps/cmdbuild/WEB-INF/lib" and delete old versions of them if exist

7- Start Tomcat and select Persian language on login page

