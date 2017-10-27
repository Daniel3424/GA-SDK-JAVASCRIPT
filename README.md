[![npm](https://img.shields.io/npm/v/gameanalytics.svg)](https://www.npmjs.com/package/gameanalytics)
[![npm](https://img.shields.io/npm/dt/gameanalytics.svg?label=npm%20downloads)](https://www.npmjs.com/package/gameanalytics)
[![MIT license](http://img.shields.io/badge/license-MIT-brightgreen.svg)](http://opensource.org/licenses/MIT)

GA-SDK-JAVASCRIPT
=================

Official repository for GameAnalytics JavaScript SDK. Written in Typescript.

Documentation is found [here](https://github.com/GameAnalytics/GA-SDK-JAVASCRIPT/wiki).

Changelog
---------
<!--(CHANGELOG_TOP)-->
**2.1.1**
* fixed null error on property 'running'

**2.1.1**
* fixed null error on property 'running'

**2.1.0**
* fixed sending events request when no events to send
* added possiblity to change event process interval

**2.0.1**
* scoped javascript sdk namespace

**2.0.0**
* changed root namespace from 'ga' to 'gameanalytics'
* it is now possible to async load library on websites to avoid any delays when loading the website (just like it is possible with Google Analytics)

**1.1.11**
* added 'construct' to version validator

**1.0.10**
* bug fix for end session when using manual session handling

**1.0.9**
* bug fix for sending events straight after initializing sdk

**1.0.8**
* removed debug log messages for release distribution versions

**1.0.7**
* version validator updated with gamemaker

**1.0.6**
* small bug fix in validator

**1.0.5**
* added os version

**1.0.4**
* bug fix for GAEvents.fixMissingSessionEndEvents

**1.0.3**
* minor dependency fixes

**1.0.2**
* enabled to use sdk via npm

**1.0.1**
* fixed debug log messages to use console.log when console.debug is not available

**1.0.0**
* bumped to v1.0.0

**0.1.0**
* initial release
