
<img style="float: right;" src="https://plone.org/logo.png">

# Awesome Plone

[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

> A community-curated list of awesome Plone addons, documentation, use-cases and other useful resources. From developers for developers.

If you want to know if there is already a package for Plone that fits your needs, searching for it on GitHub or pypi could be a real pain.
There are plenty of packages, but it's hard to understand which one could be a good solution or not.

This list is intended to fill that gap, and create a shared knowledge about common products and techniques.

We will cover only products that work with the latest major versions of Plone (currently 5.2 and 6) and only those that support Python 3.

## Contents

* [Layout](#layout)
* [Themes](#themes)
* [Content-types](#content-types)
* [Behaviors](#behaviors)
* [Authentication](#authentication)
* [Utilities](#utilities)
* [Shop](#shop)
* [Sysadmin](#sysadmin)
* [Official resources](#official-resources)

---

## Layout

_Products and resources that help developers and users to manage site layouts._

* Site/Page layout managers

  * [plone.app.mosaic](https://github.com/plone/plone.app.mosaic) - Powerful editor that allows users to compose the content of a page with different blocks.
  * [collective.cover](https://github.com/collective/collective.cover) - Allows the creation of elaborate covers built around a drag-and-drop interface.
  * [collective.editablemenu](https://github.com/RedTurtle/collective.editablemenu) - A customizable dropdown menu.

* Tiles - title are blocks of configurable content used by plone.app.mosaic.

  * [plone.app.standardtiles](https://github.com/plone/plone.app.standardtiles) - A set of standard tiles used by Mosaic, but can be used from any other tile manager.
  * [collective.tiles.advancedstatic](https://github.com/collective/collective.tiles.advancedstatic) - A tile that shows html text (similar to the static text portlet), with some additional configuration like the possibility to add custom css classes.
  * [collective.tiles.collection](https://github.com/collective/collective.tiles.collection) - A tile that shows a set of collection results with possibility to choose (and develop) custom layouts.
  * [collective.themefragments](https://github.com/collective/collective.themefragments) - Fragment tile (you need to install it in the control panel, also): Add 'tiles' TTW by using familiar 'syntax', TAL, XML and python.

* Views and utils
  * [redturtle.gallery](https://github.com/RedTurtle/redturtle.gallery) - Adds a gallery view with a carousel made with slick.

## Themes

_A set of themes developed by the community and ready-to-use._



## Content-types

_Plugins that add additional useful content-types._

* [wildcard.media](https://github.com/collective/wildcard.media) - Provides audio and video content types and behaviors.


## Behaviors
* [medialog.markdown](https://github.com/espenmn/medialog.markdown) - A markdown editor with live preview, control panel for adding shortcuts, and bling. [Demo](https://www.youtube.com/watch?v=iriCUaMsNsI)
<!--lint ignore double-link-->
* [medialog.iconpicker](https://github.com/espenmn/medialog.iconpicker) - Add icons to Plone content. Note: Important: You choose between different icon fonts in the control panel. Find a very old demo at [Demo](https://www.youtube.com/watch?v=DTzjccZG454)

## Authentication

_A list of authentication plugins, to integrate Plone with external user sources._

* [pas.plugins.ldap](https://github.com/collective/pas.plugins.ldap) - Provides users and groups from a LDAP directory.
* [pas.plugins.authomatic](https://github.com/collective/pas.plugins.authomatic) - Authomatic OAuth1/OAuth2/OpenID Login Integration with Plone.
* [pas.plugins.velruse](https://github.com/RedTurtle/pas.plugins.velruse) - Allow users to login using social networks through Velruse.

## Utilities

_Plugins that add some useful functionalities_

* [plone.restapi](https://github.com/plone/plone.restapi) - RESTful hypermedia API for Plone - comes with Plone 5.2 by default.
* [collective.easyform](https://github.com/collective/collective.easyform) - TTW form builder based on Dexterity.
* [plone.app.imagecropping](https://github.com/collective/plone.app.imagecropping) - Crops Images in Plone manually using cropper JS library.
* [collective.autoscaling](https://github.com/collective/collective.autoscaling) - Automatic scaling of (too large) images in Plone sites.
* [collective.outputfilters.enhancelinks](https://github.com/PloneGov-IT/collective.outputfilters.enhancelinks) - An additional outputfilter that enhance file and image links informations in rich text.
* [collective.lazysizes](https://github.com/collective/collective.lazysizes) - Integration of lazysizes, a lightweight lazy loader, into Plone.

## Shop

* [bda.plone.productshop](https://github.com/bluedynamics/bda.plone.productshop) - Flexible and modular e-commerce solution for Plone.


## Sysadmin

_A series of recipes/resources for running Plone and other services_

* [plone buildout](https://github.com/RedTurtle/deployments.buildout.plone) - An example of complete buildout for running Plone with different profiles for development, staging and production.
* [varnish buildout](https://github.com/RedTurtle/deployments.buildout.varnish) - An example of complete and customizable buildout for running a Varnish (cache HTTP reverse proxy) instance behind Plone.
* [haproxy buildout](https://github.com/RedTurtle/deployments.buildout.haproxy) - An example of complete and customizable buildout for running an haproxy (load balancer) instance behind Plone.
* [deployments.buildout.production](https://github.com/RedTurtle/deployments.buildout.production) - A buildout template that pulls in supervisor to manage different services like varnish, haproxy and Plone instances.


## Official resources

_Because Plone also has a lot of good official info resources_

* [plone.org](https://plone.org/) - Official website for developers and community.
* [community.plone.org](https://community.plone.org/) - Official community forum, the best place to get help.
* [Discord chat](https://discord.gg/zFY3EBbjaj) - Discord is the best way to chat with members of the Plone community.
* [Plone support](https://plone.org/support) - Where to find help.
* [docs.plone.org](https://docs.plone.org/) - Official documentation for developers/integrators.
* [training.plone.org](https://training.plone.org/) - Training classes for developers/integrators/users/designers.
* [plone.api](https://docs.plone.org/develop/plone.api/docs/index.html) - Documentation for plone.api.
