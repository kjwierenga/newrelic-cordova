New Relic Agent
================

A Cordova / PhoneGap plugin to add the New Relic Mobile Agent to your application. (Currently iOS only)

__NOTE:__ This plugin requires Cordova / PhoneGap >= 3.3.0 in order to support installation and linking of custom frameworks.

Installation
===============

`cordova plugin install com.newrelic.cordova`

Configuration
===============

Get your mobile app's token from the New Relic portal and add it to your `config.xml` like so:

`<preference name="NewRelicApplicationToken" value="YOUR_TOKEN_HERE" />

License
==============

The code for this plugin is covered under the Apache 2 License. See the [license file](LICENSE).

__NOTE:__ This license only applies to the *plugin code*. Please see the [New Relic license file](src/ios/NewRelicFramework/LICENSE) for the license that applies to the New Relic framework code.
