ckanext-introjs
===============

This plugin adds `intro.js` goodness to CKAN - a library to create better
introductions for websites and features with a step-by-step guide for your
UI (so the `intro.js` website says - https://usablica.github.io/intro.js/).

Originally created for use on civil servants in NHS England with mixed
results.

YMMV - please feel free to fork this repository.

;-)

Usage
=====

After installing the plugin in the usual manner please ensure the following
steps are taken:

* Ensure that both the CSS and Javascript is correctly referenced within the appropriate template. For example, `<link rel="stylesheet" href="/css/introjs.min.css" />` and `<script type="text/javascript" src="/js/intro.min.js"></script>` should appear in some sort of base template.
* To start the plugin in the UI ensure you create a link or button like this: `<a href="javascript:void(0)" onClick="javascript:introJs().start();" data-intro="Clicking the 'Help' link will display on-page walkthrough information. Click the 'Next' and 'Back' buttons below to navigate the walkthrough. Clicking 'Skip' returns you to the page." data-step="1">Help</a>`.
* More information on how to configure the Javascript and how this interacts with HTML tags and elements in your templates can be found at the `intro.js` website: https://github.com/usablica/intro.js
