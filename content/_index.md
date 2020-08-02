# Personal projects I've been working on:
- **[Impetuous](https://github.com/adrhumphreys/impetuous):** A project to statically cache responses via middleware in Silverstripe. Designed to be extended on due to the amount of different circumstances/context each project has.
- **[Telescope](https://github.com/adrhumphreys/telescope):** A reimplementation of Laravels Telescope in Silverstripe. Front end is written as a SPA in React.
- **[Recipes](https://github.com/adrhumphreys/recipes):** A recipe website built for my partner. Uses Gatsby for the frontend and stores files in markdown to use with Netlify CMS for free hosting and easy editing. View it [here](http://jar.nz).
- **[Safezone](https://github.com/adrhumphreys/safe-zone):** Basic react app used to create "safe zones" for images based on ratios

## Some of the open source contributions I've made:
- [Silverstripe Assets (recursive performance issue)](https://github.com/silverstripe/silverstripe-assets/pull/415): Read more about it [here](/posts/silverstripe-assets/).
- [Silverstripe Assets (`Folder::find_or_make` bug fix)](https://github.com/silverstripe/silverstripe-assets/pull/364): This was found when trying to track down why folders were being duplicated in the database.
- [Silverstripe CMS (Increase performance of the CMS through caching)](https://github.com/silverstripe/silverstripe-cms/pull/2493): When profiling the CMS performance for a client web site I found that 7ish% of the time for a request was taken up by generating CSS classes for page icons.
- [Silverstripe CMS (Reduce complexity)](https://github.com/silverstripe/silverstripe-cms/pull/2476): Removed code for checking if an item was archived that was implemented differently elsewhere.
- [Silverstripe Versioned (Fix incorrect state)](https://github.com/silverstripe/silverstripe-versioned/pull/243): When `DataObjects` were archived the instance of the `DataObject` would retain their previous version.
