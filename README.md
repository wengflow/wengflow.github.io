# My Personal Website

[![Continuous Deployment Status](https://github.com/low5545/low5545.github.io/workflows/Deploy/badge.svg?branch=source&event=push)](https://github.com/low5545/low5545.github.io/actions?query=workflow%3ADeploy+event%3Apush)

This personal website is based on the [al-folio](https://github.com/alshedivat/al-folio) theme. It is statically generated with [Jekyll](https://jekyllrb.com) and hosted on [GitHub Pages](https://pages.github.com). The `source` and `master` branch of this repository houses the source files and generated static content of this website respectively. When commits are pushed to the `source` branch, a [GitHub Actions](https://github.com/features/actions) workflow will be triggered for automated website deployment. 

An [Anaconda](https://www.anaconda.com) environment, with `ruby` and `clangxx_osx-64` packages installed, is used for development on macOS. It is important to ensure `ruby` is installed from the `conda-forge` channel to prevent gem native extension build errors. This happens at least on `ruby v2.5.1` from the default `anaconda` channel.

The favicon used in this website is a modification of this [robot icon](https://www.flaticon.com/free-icon/robot_1006195?term=robot&page=1&position=12&related_item_id=1006195) designed by [Freepik](https://www.flaticon.com/authors/freepik) from [Flaticon](https://www.flaticon.com). The [RealFaviconGenerator](https://realfavicongenerator.net) is used to generate favicon files and HTML markups from an SVG vector image for compatability with various browsers and platforms.
