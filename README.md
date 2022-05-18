# Awesome Plone [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

[<img align="right" src="https://plone.org/logo.png">](https://plone.org)

> A community-curated list of _awesome_ Plone addons, documentation, use-cases and other useful resources. From developers for developers.

[Plone](https://plone.org) is a content management system with unsurpassed functionality and customizability out of the box.  The entire software stack for Plone is open source. Plone is governed by a non-profit foundation and a community of volunteers. Plone is unique among CMSes for the many high-end features it provides out-of-the-box.

If you want to know if there is already a add-on for Plone that fits your needs, searching for it on GitHub or pypi can be a real pain.
There are plenty of packages, but it's hard to understand which one could be a good solution or not.

This list is intended to fill that gap, and create a shared knowledge about common products and techniques.

This list only covers add-ons and resources that work with the latest major versions of Plone (currently 5.2 and 6) and only those that support Python 3.

## Contributing

Contributions are welcome! Read the [contribution guidelines](contributing.md).

## Contents

* [Layout](#layout)
* [Themes](#themes)
* [Content-types](#content-types)
* [Behaviors](#behaviors)
* [Authentication](#authentication)
* [Utilities](#utilities)
* [Shop](#shop)
* [Develop](#develop)
* [Sysadmin](#sysadmin)
* [Official resources](#official-resources)

---

## Layout

_Products and resources that help developers and users to manage site layouts._

* Site/Page layout managers

  * [plone.app.mosaic](https://github.com/plone/plone.app.mosaic) - Powerful editor that allows users to compose the content of a page with different blocks.
  * [collective.cover](https://github.com/collective/collective.cover) - Allows the creation of elaborate covers built around a drag-and-drop interface.
  * [collective.contentsections](https://github.com/collective/collective.contentsections) - This product offers a block approach for Plone 6 Classic based entirely on Dexterity content types.

  * [collective.editablemenu](https://github.com/RedTurtle/collective.editablemenu) - A customizable dropdown menu.

* Tiles - title are blocks of configurable content used by plone.app.mosaic.

  * [collective.tiles.carousel](https://github.com/collective/collective.tiles.carousel) - A slider tile for plone.app.mosaic based on the carousel component of Bootstrap 5.
  * [plone.app.standardtiles](https://github.com/plone/plone.app.standardtiles) - A set of standard tiles used by Mosaic, but can be used from any other tile manager.
  * [collective.tiles.advancedstatic](https://github.com/collective/collective.tiles.advancedstatic) - A tile that shows html text (similar to the static text portlet), with some additional configuration like the possibility to add custom css classes.
  * [collective.tiles.collection](https://github.com/collective/collective.tiles.collection) - A tile that shows a set of collection results with possibility to choose (and develop) custom layouts.
  * [collective.themefragments](https://github.com/collective/collective.themefragments) - Fragment tile (you need to install it in the control panel, also): Add 'tiles' TTW by using familiar 'syntax', TAL, XML and python.

* Views and utils
  * [redturtle.gallery](https://github.com/RedTurtle/redturtle.gallery) - Adds a gallery view with a carousel made with slick.


## Media

_Plugins that handle image, video and audio content._

* [plone.app.imagecropping](https://github.com/collective/plone.app.imagecropping) - Crops Images in Plone manually using cropper JS library.
* [collective.autoscaling](https://github.com/collective/collective.autoscaling) - Automatic scaling of (too large) images in Plone sites.
* [plone.gallery](https://github.com/plone/plone.gallery) - Photo gallery view for Plone.
* [collective.behavior.banner](https://github.com/collective/collective.behavior.banner) - A behavior to create banners and sliders from banners.
* [wildcard.media](https://github.com/collective/wildcard.media) - Provides audio and video content types and behaviors.
* [collective.wavesurfer](https://github.com/collective/collective.wavesurfer) - Implementation of https://wavesurfer-js.org audio player for Plone.


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
* [collective.easyform](https://github.com/collective/collective.easyform) - EasyForm provides a Plone form builder through-the-web using fields, widgets, actions and validators. Form input can be saved or emailed. A simple and user-friendly interface allows non-programmers to create custom forms.
* [plone.app.imagecropping](https://github.com/collective/plone.app.imagecropping) - Crops Images in Plone manually using cropper JS library.
* [collective.autoscaling](https://github.com/collective/collective.autoscaling) - Automatic scaling of (too large) images in Plone sites.
* [collective.outputfilters.enhancelinks](https://github.com/PloneGov-IT/collective.outputfilters.enhancelinks) - An additional outputfilter that enhance file and image links informations in rich text.
* [collective.lazysizes](https://github.com/collective/collective.lazysizes) - Integration of lazysizes, a lightweight lazy loader, into Plone.

## Shop

* [bda.plone.productshop](https://github.com/bluedynamics/bda.plone.productshop) - Flexible and modular e-commerce solution for Plone.


## Develop

_Add-ons that help developing Plone_

* [Products.PDBDebugMode](https://github.com/collective/Products.PDBDebugMode) - Post-mortem debugging: open a pdb session whenever an exception occurs so you you can find out what is going wrong. Plus: By adding /pdb to a url you end up you in a pdb session on the current context. A killer tool for developers.
* [plone.reload](https://github.com/plone/plone.reload) - Code and configuration reload without server restarts.
* [Products.PrintingMailHost](https://github.com/collective/Products.PrintingMailHost) - Log mail messages instead of sending mail.
* [collective.exportimport](https://github.com/collective/collective.exportimport/) - Export and import content and a lot of other data from and to Plone. The main solution for all kinds of migrations.
* [collective.impersonate](https://github.com/collective/collective.impersonate) - Allow administrators to impersonate another user. Useful for verifying workflow/permission set up on real content.
* [experimental.gracefulblobmissing](https://github.com/collective/experimental.gracefulblobmissing/) - Gracefully handle missing binary files in Plone.
* [collective.relationhelpers](https://github.com/collective/collective.relationhelpers) - Helpers to manage, create, export and rebuild relations in Plone 5.x. For Plone 6 this was merged into Plone core.


## Sysadmin

_Add-ons that help admins deploying and maintaining Plone_

* [collective.fingerpointing](https://github.com/collective/collective.fingerpointing) - Keeps track of different events and write them down to an audit log.
* [collective.recipe.backup](https://github.com/collective/collective.recipe.backup) - Powerful and flexible backup/restore solution for Plone.
* [collective.revisionmanager](https://github.com/collective/collective.revisionmanager) - Manage Products.CMFEditions histories that can bloat your database.
* [collective.sentry](https://github.com/collective/collective.sentry) - Sentry integration to aggregate errors and help finding their causes.
* [collective.xkey](https://github.com/collective/collective.xkey) - Use Varnish's xkey module for tag-based cache invalidation in Plone.
* [haufe.requestmonitoring](https://github.com/collective/haufe.requestmonitoring) - Detailed request logging functionality on top of the publication events. Useful to find out what takes longer than it should.


## Official resources

_Because Plone also has a lot of good official info resources_

* [plone.org](https://plone.org/) - Official website for developers and community.
* [community.plone.org](https://community.plone.org/) - Official community forum, the best place to get help.
* [Discord chat](https://discord.gg/zFY3EBbjaj) - Discord is the best way to chat with members of the Plone community.
* [Plone support](https://plone.org/support) - Where to find help.
* [docs.plone.org](https://docs.plone.org/) - Official documentation for developers/integrators.
* [training.plone.org](https://training.plone.org/) - Training classes for developers/integrators/users/designers.
* [plone.api](https://docs.plone.org/develop/plone.api/docs/index.html) - Documentation for plone.api.
