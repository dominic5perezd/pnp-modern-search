!["PnP"](https://pnp.github.io/images/hero-parker-p-1080.png){: .center .logo}

# PnP Modern Search v4 (preview)

The PnP 'Modern Search' solution is a set of SharePoint Online modern Web Parts allowing SharePoint super users, webmasters and developers to create highly flexible and personalized search based experiences in minutes.

**The v3 documentation is available [here](https://web.archive.org/web/20201103152956/https://microsoft-search.github.io/pnp-modern-search/)**

!!! important "PnP Modern Search v3.x deprecation"
    **The v4 version (this version) uses a brand new code architecture and replaces the older v3 codebase**. As a result, all v3.x versions are now considered as deprecated. Because not all features from v3.x exist in v4.x yet, you can still use the v3.x packages to meet your requirements if v4.x doesn't do the job for you. However, the main focus is now on the new v4 version. Nothing personal ;)

    **v3 and v4 don't share the same Web Part and solution IDs meaning you can have them side by side on a page if necessary without overlap. However, in this case, you will have to rename *.sppkg files to be able to upload both versions in your App Catalog because they share the same SPFx package name `pnp-modern-search-parts.sppkg`.**
    
    !["V3 & v4"](./assets/v3_v4.png){: .center}

## What's included?

The solution includes the following Web Parts:

| Component | Description |
| --------- | ----------- |
| **[Search Results](./usage/search-results/index.md)** | Retrieve data from a data source and render them in a specific layout.
| **[Search Filters](./usage/search-filters/index.md)** | Filter and refine data displayed in 'Search Results' Web Parts.
| **[Search Verticals](./usage/search-verticals/index.md)** | Browse data as silos (i.e. tabs) from multiple data sources.
| **[Search box](./usage/search-box/index.md)** | Let users enter free text queries sent to 'Search Results' Web Parts.

## Supported browsers

Here is the list of supported browsers:

- Chrome
- Firefox
- Edge
- Edge Chromium
- Brave

**We don't support Internet Explorer 11**. We think there are plenty of other options for enteprise scenarios in the market. Maybe it's time to move on. For developers, it represents an **huge** ammount of time to make the solution compatible for a very low benefit. Hope you understand, ain't personal ;).

## Extensibility model

By getting this solution, you also benefit from an advanced [extensibility model](./extensibility/index.md) allowing you to customize the solution according to your requirements if default features don't do the job for you. 

**The supported extensions are:**

- [Custom web components](./extensibility/custom_web_component.md).
- [Custom suggestions providers](./extensibility/custom_suggestions_provider.md).
- [Custom Handlebars customization (helpers, partials, etc.)](./extensibility/handlebars_customizations.md).

With these available customizations options, you can do pretty much anything!

## Troubleshooting

If you encounter an issue, please use the GitHub issues list of [this repository](https://github.com/microsoft-search/pnp-modern-search/issues). Also, to help us to resolve your issue, you can include screenshots or error messages coming from:

- The faulty Web Part itself. 
- Errors displayed in the browser console (typically pressing F12).
- Errors displayed in the SharePoint console (pressing CTRL+F12)

## Issues, questions, feedback?

For any issue, question or feedback, please the [official GitHub repository](https://github.com/microsoft-search/pnp-modern-search/issues). We will be happy to help you!

## About

PnP Modern Search version 4 initially made by [Franck Cornu](https://twitter.com/FranckCornu) based on a fork of the [@aequos 'Modern Data Visualizer'](https://www.aequos.ca/) solution.

## Maintainers & contributors

Here is the list of main contributors of the PnP Modern Search (all versions included)

- Franck Cornu (aequos) - [@FranckCornu](http://www.twitter.com/FranckCornu)
- Mikael Svenson (Microsoft) - [@mikaelsvenson](http://www.twitter.com/mikaelsvenson)
- Yannick Reekmans - [@yannickreekmans](https://twitter.com/yannickreekmans)
- Albert-Jan Schot - [@appieschot](https://twitter.com/appieschot)
- Tarald Gåsbakk (PuzzlePart) - [@taraldgasbakk](https://twitter.com/Taraldgasbakk)
- Brad Schlintz (Microsoft) - [@bschlintz](https://twitter.com/bschlintz)
- Richard Gigan - [@PooLP](https://twitter.com/PooLP)
- Matthew Stark