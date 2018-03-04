[![Plone](https://plone.org/logo.png)](https://plone.org)

# Awesome Plone [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

> A community-curated list of awesome Plone addons, documentation, use-cases and other useful resources.

This list doesn't wants to replace [official website](https://plone.org/) or [documentation](https://docs.plone.org),
but wants to be a quick and complete cheatsheet with a list of most used components and techniques by Plone integrators and developers.

This list will cover only products that works with the latest major version of Plone (5).

## Contents

* [Layout](#layout)
* [Themes](#themes)
* [Content-types](#content-types)
* [Authentication](#authentication)
* [Utilities](#utilities)
* [Sysadmin](#sysadmin)
* [Official resources](#official-resources)

---

## Layout

_Products and resources that helps developers and users to manage site layouts._

* Site/pages layout managers

  * [plone.app.mosaic](https://github.com/plone/plone.app.mosaic) - Powerful editor that allows users to compose the content of a page with different blocks.
  * [redturtle.tiles.management](https://github.com/RedTurtle/redturtle.tiles.management) - A tiles management system, easier than plone.app.mosaic (doesn't allow to compose pages on a grid system). Useful for example for one-column pages.
  * [collective.editablemenu](https://github.com/RedTurtle/collective.editablemenu) - A customizable dropdown menu.

* Tiles

  * [plone.app.standardtiles](https://github.com/plone/plone.app.standardtiles) - A set of standard tiles used by Mosaic, but can be used from any other tile manager.
  * [collective.tiles.advancedstatic](https://github.com/collective/collective.tiles.advancedstatic) - A tile that shows html text (similar to the text portlet), with some additional configuration like the possibility to add custom css style classes.
  * [collective.tiles.collection](https://github.com/collective/collective.tiles.collection) - A tile that shows a set of collection results with possibility to choose (and develop) custom layouts.

* Views and utils
  * [collective.slick](https://github.com/collective/collective.slick) - Add slick carousel to Plone resources.
  * [redturtle.patterns.slider](https://github.com/RedTurtle/redturtle.patterns.slider) - A pattern based on Plone Mockup that enable a slick slider on a selected div.
  * [redturtle.gallery](https://github.com/RedTurtle/redturtle.gallery) - adds a gallery view with a carousel made with slick.

## Themes

_A set of themes developed by the community and ready-to-use._

_...work in progress_

## Content-types

_Plugins that add additional useful content-types._

* [wildcard.media](https://github.com/collective/wildcard.media) - Provides audio and video content types and behaviors.

## Authentication

_A list of authentication plugins, to integrate Plone with external user sources._

* [Products.PloneLDAP](https://github.com/collective/Products.PloneLDAP) - Connect Plone to LDAP/ActiveDirectory.
* [pas.plugins.authomatic](https://github.com/collective/pas.plugins.authomatic) - Authomatic OAuth1/OAuth2/OpenID Login Integration with Plone.
* [pas.plugins.velruse](https://github.com/RedTurtle/pas.plugins.velruse) - Allow users to login using social networks through Velruse.

## Utilities

_Plugins that add some useful functionalities_

* [plone.restapi](https://github.com/plone/plone.restapi) - RESTful hypermedia API for Plone.
* [plone.app.imagecropping](https://github.com/collective/plone.app.imagecropping) - Crops Images in Plone manually using cropper JS library.
* [collective.outputfilters.enhancelinks](https://github.com/PloneGov-IT/collective.outputfilters.enhancelinks) - outputfilter that add mimetype icon and filesize to file/images linked in TinyMCE fields.
* [collective.lazysizes](https://github.com/collective/collective.lazysizes) - Integration of lazysizes, a lightweight lazy loader, into Plone.
* [collective.easyform](https://github.com/collective/collective.easyform) - TTW form builder based on Dexterity.

* [collective.limitfilesizepanel](https://github.com/RedTurtle/collective.limitfilesizepanel/issues) - Configure the size limit of files and images fields through a control panel.
* [collective.analyticspanel](https://github.com/RedTurtle/collective.analyticspanel/issues) - Add more control over the inclusion of JavaScript analytics code of your Plone site with a configurable control panel.

## Sysadmin

_A series of recipes/resources for running Plone and other services_

* [plone buildout](https://github.com/RedTurtle/deployments.buildout.plone) - An example of complete buildout for running Plone with different profiles for development, staging and production.
* [varnish buildout](https://github.com/RedTurtle/deployments.buildout.varnish) - An example of complete and customizable buildout for running a Varnish (cache HTTP reverse proxy) instance behind Plone.
* [haproxy buildout](https://github.com/RedTurtle/deployments.buildout.haproxy) - An example of complete and customizable buildout for running an haproxy (load balancer) instance behind Plone.
* [deployments.buildout.production](https://github.com/RedTurtle/deployments.buildout.production) - A buildout template that pulls in supervisor to manage different services like varnis, haproxy and Plone instances.

## Official resources

_Because Plone has also a lot of good official resources where find infos_

* [plone.org](https://plone.org/) - Official website.
* [community.plone.org](https://community.plone.org/) - Official community forum.
* [docs.plone.org](https://docs.plone.org/) - Official documentation for developers/integrators.
* [plone.api](https://docs.plone.org/develop/plone.api/docs/index.html) - Documentation for plone.api.
* [slack channel](https://plone.slack.com) - Official slack channel.
* [gitter channel](https://gitter.im/plone/home) - Official gitter channel.
* #plone irc channel.

## License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)
