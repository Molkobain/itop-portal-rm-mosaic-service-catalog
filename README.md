👋 [Available on Molkobain I/O!](https://www.molkobain.com/product/remove-mosaic-view-from-service-catalog/)

# iTop extension: molkobain-portal-rm-mosaic-service-catalog

### Description
Remove the *mosaic* view from the service catalog of the user portal.

*Note: This extension will fail to install if the mosaic view has already be removed from the service catalog. Also, you must define the default view to something else then mosaic or the portal will crash.*

*Before*

![Description decoration](https://raw.githubusercontent.com/Molkobain/itop-portal-rm-mosaic-service-catalog/master/docs/mprmsc-service-catalog-before.PNG)

*After*

![Description decoration](https://raw.githubusercontent.com/Molkobain/itop-portal-rm-mosaic-service-catalog/master/docs/mprmsc-service-catalog-after.PNG)

### Compatibility
Compatible with iTop 2.4+

### Installation
* Unzip the extension
* Copy the ``dist/molkobain-portal-rm-mosaic-service-catalog`` folder under ``<PATH_TO_ITOP>/extensions`` folder of your iTop
* Run iTop setup & select extension *Portal: Remove mosaic mode from service catalog*

*Your folders should look like this*

![Extensions folder](https://raw.githubusercontent.com/Molkobain/itop-portal-rm-mosaic-service-catalog/master/docs/mprmsc-install.PNG)

### Configuration
#### Standard portal
No configuration needed.

#### Customized portal
If you customized the user portal, you will have to check/modify 2 things on the ``datamodel.molkobain-portal-rm-mosaic-service-catalog.xml`` file of the extension, then run an iTop setup.
* Portal ID: If your portal ID is not ``itop-portal``, change it to your custom ID on line 4.
* Service catalog brick: If you are not targetting the standard service catalog, change the brick ID on line 6 (``services``) with yours.

### Licensing
This extension is under [MIT license](https://en.wikipedia.org/wiki/MIT_License).
