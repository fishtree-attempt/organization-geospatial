> **ATTENTION** This is an experimental test of [The Carpentries Workbench](https://carpentries.github.io/workbench) lesson infrastructure.
> It was automatically converted from the source lesson via [the lesson transition script](https://github.com/carpentries/lesson-transition/).
> 
> If anything seems off, please contact Zhian Kamvar [zkamvar@carpentries.org](mailto:zkamvar@carpentries.org)

[![DOI](https://zenodo.org/badge/128227810.svg)](https://zenodo.org/badge/latestdoi/128227810)
![Build and Deploy Website](https://github.com/datacarpentry/organization-geospatial/actions/workflows/deploy.yml/badge.svg)
[![Create a Slack Account with us](https://img.shields.io/badge/Create_Slack_Account-The_Carpentries-071159.svg)](https://swc-slack-invite.herokuapp.com/)
[![Slack Status](https://img.shields.io/badge/Slack_Channel-dc--geospatial-E01563.svg)](https://swcarpentry.slack.com/messages/C9ME7G5RD)

# Geospatial Data Organization

This lesson is built and deployed automatically on Travis CI. All changes should only be made in the `master` branch.

## Contributing to lesson development

- The lesson files to be edited are in the `_epiodes_rmd` folder. This repository uses the `master` branch for development.
- You can visualize the changes locally by typing `make serve` at your terminal. The site will be rendered at [http://localhost:4000](https://localhost:4000)
- Each time you push a change to GitHub, Travis-CI rebuilds the lesson, and when it's successful (look for the green badge at the top of the README file), it publishes the result at [http://www.datacarpentry.org/organization-geospatial/](https://www.datacarpentry.org/organization-geospatial/)
- Note: any manual commit to `gh-pages` will be erased and lost during the automated build and deploy cycle operated by Travis-CI.


