# Bootstrap 4 templates for CMSMS

A set of generic Bootstrap4-based templates and plugins for the CMS Made Simple templating system.

It provides a central *settings* file to easily change the template, and a few standard templates:

* A triple-column layout for simple pages.
* A nine-column layout for longer pages
* A variant of the nine-column layout with a Jumbotron at the top
* A minimal page suitable for alternate content types (JSON, XML, etc)
* Templates for the following modules:  
  * News
  * Blog
  * Gallery
  * FormBuilder

All content areas have a `class` field that defaults to `col-12`. This can be be replaced with any valid Bootstrap classes.

### Dependencies:

The templates require the following CMSMS modules to be installed:

* CGSmartImage
* CGExtensions
* CSSPreProcessor
* SitemapMgr
* Markdown

Optional CMSMS Modules
* FormBuilder
* Captcha
