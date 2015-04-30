### Sencha Ext.Direct connector for node.js

Important: Version 2.0.0 and up is not compatible with previous 1.x branch

#### Compatibility:
* Sencha Touch 2.3+
* ExtJs 4.2.x+
* ExtJs 5+

#### Example code
Sample applications for Touch and ExtJs can be found here: https://github.com/jurisv/extdirect.examples

ExtJS:

    * Application structure with API provider
    * Grid CRUD Master-detail
    * Cookie / Session
    * Direct method call, shows regular call and onw that has hard exception (syntax error)
    * Form Load / Submit
    * Form file upload (Cross domain upload is not supported!)
    * Tree root / child dynamic load
    * Metadata (Starting from ExtJS 5)
    * Namespaces (From 4.2)

Sencha Touch:

    * Application structure with API provider
    * List read using directFn
    * Form load / submit

#### Usage

TODO



### Changelog:
* 2.0.0 (TBD)

    * Comment source code and use descriptive variable names #21
    * Implement namespaced Classes to have nested actions #29 See below
    * Add namespace support (nested Actions) You can now organize files using folders
    * More streamlined definition for metadata and formHandler  (//@meta and //@formHandler )
    * Exclude non .js files from API discovery
    * Separate route paths for classes (classRouteUrl and classPath)
    * Use latest Express framework in examples, closes #28

### Todo

    * Improve callback support #30
    * Add support for metadata #27 (have to provide example)


