### SIMToolbox: a MATLAB toolbox for structured illumination microscopy

SIMToolbox is an open-source, modular set of functions for MATLAB designed for processing data acquired by structured illumination microscopy. Both optical sectioning and super-resolution applications are supported. The software is also capable of maximum a posteriori probability image estimation (MAP-SIM), an alternative method for reconstruction of structured illumination images. MAP-SIM can potentially reduce reconstruction artifacts, which commonly occur due to refractive index mismatch within the sample and to imperfections in the illumination.

Authors: Pavel Křížek, Tomáš Lukeš, Martin Ovesný, Jakub Pospíšil, Vojtěch Terš, Karel Fliegel, and Guy M. Hagen

---

Published in:
- GigaScience, April 2020, doi: [10.1093/gigascience/giaa035](https://doi.org/10.1093/gigascience/giaa035)
- GigaScience, January 2019, doi: [10.1093/gigascience/giy126](https://doi.org/10.1093/gigascience/giy126)
- Bioinformatics, October 2015, doi: [10.1093/bioinformatics/btv576](https://doi.org/10.1093/bioinformatics/btv576)

# The Minimal theme
## Usage

To use the Minimal theme:

1. Add the following to your site's `_config.yml`:

    ```yml
    theme: jekyll-theme-minimal
    ```

2. Optionally, if you'd like to preview your site on your computer, add the following to your site's `Gemfile`:

    ```ruby
    gem "github-pages", group: :jekyll_plugins
    ```



## Customizing

### Configuration variables

Minimal will respect the following variables, if set in your site's `_config.yml`:

```yml
title: [The title of your site]
description: [A short description of your site's purpose]
```

Additionally, you may choose to set the following optional variables:

```yml
logo: [Location of the logo]
show_downloads: ["true" or "false" to indicate whether to provide a download URL]
google_analytics: [Your Google Analytics tracking ID]
```

### Stylesheet

If you'd like to add your own custom styles:

1. Create a file called `/assets/css/style.scss` in your site
2. Add the following content to the top of the file, exactly as shown:
    ```scss
    ---
    ---

    @import "{{ site.theme }}";
    ```
3. Add any custom CSS (or Sass, including imports) you'd like immediately after the `@import` line

### Layouts

If you'd like to change the theme's HTML layout:

1. [Copy the original template](https://github.com/pages-themes/minimal/blob/master/_layouts/default.html) from the theme's repository<br />(*Pro-tip: click "raw" to make copying easier*)
2. Create a file called `/_layouts/default.html` in your site
3. Paste the default layout content copied in the first step
4. Customize the layout as you'd like

## Roadmap

See the [open issues](https://github.com/pages-themes/minimal/issues) for a list of proposed features (and known issues).

## Project philosophy

The Minimal theme is intended to make it quick and easy for GitHub Pages users to create their first (or 100th) website. The theme should meet the vast majority of users' needs out of the box, erring on the side of simplicity rather than flexibility, and provide users the opportunity to opt-in to additional complexity if they have specific needs or wish to further customize their experience (such as adding custom CSS or modifying the default layout). It should also look great, but that goes without saying.

## Contributing

Interested in contributing to Minimal? We'd love your help. Minimal is an open source project, built one contribution at a time by users like you. See [the CONTRIBUTING file](docs/CONTRIBUTING.md) for instructions on how to contribute.

### Previewing the theme locally

If you'd like to preview the theme locally (for example, in the process of proposing a change):

1. Clone down the theme's repository (`git clone https://github.com/pages-themes/minimal`)
2. `cd` into the theme's directory
3. Run `script/bootstrap` to install the necessary dependencies
4. Run `bundle exec jekyll serve` to start the preview server
5. Visit [`localhost:4000`](http://localhost:4000) in your browser to preview the theme

### Running tests

The theme contains a minimal test suite, to ensure a site with the theme would build successfully. To run the tests, simply run `script/cibuild`. You'll need to run `script/bootstrap` one before the test script will work.

<!--
**simtoolbox/SIMToolbox** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.
