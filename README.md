<h1 align="center">RedM Profiles</h1>

<p align="center">
  <i>Multi-account system for RedM built to compliment <a href="https://github.com/Ascent-Gaming/redm-user">redm-user</a></i>
  <br>
  <br>
  <a href="https://github.com/Ascent-Gaming/redm-profiles/blob/master/LICENSE">
    <img src="https://img.shields.io/badge/License-MIT-blue.svg?style=flat" alt="License: MIT">
  </a>
  <a href="https://github.com/Ascent-Gaming/redm-profiles/commits/master">
    <img src="https://img.shields.io/github/last-commit/Ascent-Gaming/redm-profiles.svg?style=flat" alt="Last commit">
  </a>
  <a href="">
    <img src="https://img.shields.io/github/workflow/status/Ascent-Gaming/redm-profiles/Node.js%20CI" alt="Workflow">
  </a>
</p>

## Overview

Multi-accounts for RedM independent any other framework or gamemode. This resource intends to provide a base, ambigious any one type of gamemode. In other words, **not** calling this resource `redm-characters` was a deliberate choice.

This resource only handles the creation, managment, and selection of profiles. What is done afterwards, including *"character creation"*, has been intentionally left out; to be handled by another resource.

The UI for this resource can be found at [`Ascent-Gaming/redm-profiles-ui`](). It is hosted seperate this repository to make editing the UI to fit your own taste can be done easily.

For example, this repository loads the UI using [`git modules`](). By setting this module to your own fork of the UI, and by sticking to the API it uses to communicate with the `client` resource, you can quickly load your own and other's variations.

## Dependencies

The following dependencies and their dependencies are required by this resource.

- [`mysql-async`](https://github.com/amakuu/mysql-async-temporary)
- [`redm-user`](https://github.com/Ascent-Gaming/redm-user)

## Installation

1. Install all of the dependencies required by this resource.
2. `clone` or download this repository into your server's `./resources/` directory.
3. Rename the directory (or specify a name when `cloning`) to your liking.
4. Aftering ensuring its installed, run `yarn install` in this resources's directory.
5. Build the resource using `yarn build`.
6. `ensure` this resource *after* any of its dependencies.

## Features

## License
This product is MIT licensed. Please make sure you give credit and include this license in your product.
