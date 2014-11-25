WebComponents.net
=================

According to The W3C Web Applications (WebApps) Working Group, Web Components are "the component model for the Web"
and include specifications for the following features:
  - Templates, which define chunks of markup that are inert but can be activated for use later.
  - Decorators, which define chunks of markup that are inert but can be activated for use later.
  - Custom Elements, which let authors define their own elements, with new tag names and new script interfaces.
  - Shadow DOM, which encapsulates a DOM subtree for more reliable composition of user interface elements.
  - Imports, which defines how templates, decorators and custom elements are packaged and loaded as a resource.

This project aims to provide tools to easily incorporate these features into ASP.NET-based web sites.  The initial emphasis is on ASP.NET MVC projects utilizing Razor and C#, but the intent is to develop tools and utilities that will be appropriate for any ASP.NET web site, regardless of flavor.

Several libraries focus on making Web Components available for general use in mainstream browsers, notably Bosonic, Polymer, WebComponents.js, and X-Tag.  Generally, these projects provide polyfills that enable existing browsers to correctly display pages that include Web Components, even if the browsers do not understand Web Components as part of their native capabilities.  For more information, please see WebComponents.org or www.Polymer-project.org.

This project (WebComponents.net) starts with the two ideas that (1) Web Components will be a very important feature of web development in the coming years and (2) the various technologies associated with ASP.NET will benefit from some specialized assistance in implementing Web Components.  For example, HTMLHelpers could quickly add the power of Web Components to ASP.NET MVC Views.
