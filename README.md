# My Personal Website

[![Continuous Deployment Status](https://github.com/wengflow/wengflow.github.io/workflows/deploy/badge.svg?branch=master&event=push)](https://github.com/wengflow/wengflow.github.io/actions?query=workflow%3Adeploy+event%3Apush)

This personal website is based on the [al-folio](https://github.com/alshedivat/al-folio) theme. It is statically generated with [Jekyll](https://jekyllrb.com) and hosted on [GitHub Pages](https://pages.github.com). The `master` and `gh-pages` branch of this repository houses the source files and generated static content of this website respectively. When commits are pushed to the `master` branch, a [GitHub Actions](https://github.com/features/actions) workflow will be triggered for automated website deployment.

A [Conda](https://conda.io/) environment is used for the development of this website. To set up an environment with the relevant dependencies, run:
```bash
conda env create -f environment.yml
npm install -g mermaid.cli
```

The favicon used in this website is a modification of this [robot icon](https://www.flaticon.com/free-icon/robot_1006195?term=robot&page=1&position=12&related_item_id=1006195) designed by [Freepik](https://www.flaticon.com/authors/freepik) from [Flaticon](https://www.flaticon.com). The [RealFaviconGenerator](https://realfavicongenerator.net) is used to generate favicon files and HTML markups from an SVG vector image for compatability with various browsers and platforms.
