# This plugin is deprecated.

We recommend you use [Black](https://github.com/ambv/black) instead.

---

<div align="center">
<img alt="Prettier"
  src="https://cdn.rawgit.com/prettier/prettier-logo/master/images/prettier-icon-light.svg">
<img alt="Python"
  hspace="25"
  height="210"
  src="https://upload.wikimedia.org/wikipedia/commons/c/c3/Python-logo-notext.svg">
</div>

<h2 align="center">Prettier Python Plugin</h2>

<p align="center">
  <a href="https://gitter.im/jlongster/prettier">
    <img alt="Gitter" src="https://img.shields.io/gitter/room/jlongster/prettier.svg?style=flat-square">
  </a>
  <a href="https://travis-ci.org/prettier/prettier-python">
    <img alt="Travis" src="https://img.shields.io/travis/prettier/plugin-python/master.svg?style=flat-square">
  </a>
  <a href="https://www.npmjs.com/package/@prettier/plugin-python">
    <img alt="npm version" src="https://img.shields.io/npm/v/@prettier/plugin-python.svg?style=flat-square">
  </a>
  <!-- <a href="https://www.npmjs.com/package/@prettier-plugin-python">
    <img alt="monthly downloads" src="https://img.shields.io/npm/dm/@prettier/plugin-python.svg?style=flat-square">
  </a> -->
  <a href="#badge">
    <img alt="code style: prettier" src="https://img.shields.io/badge/code_style-prettier-ff69b4.svg?style=flat-square">
  </a>
  <a href="https://twitter.com/PrettierCode">
    <img alt="Follow+Prettier+on+Twitter" src="https://img.shields.io/twitter/follow/prettiercode.svg?label=follow+prettier&style=flat-square">
  </a>
</p>

## WORK IN PROGRESS

Please note that this plugin is under active development, and might not be ready to run on production code yet.

## Contributing

If you're interested in contributing to the development of Prettier for Python, you can follow the [CONTRIBUTING guide from Prettier](https://github.com/prettier/prettier/blob/master/CONTRIBUTING.md), as it all applies to this repository too.

To test it out on a Python file:

* Clone this repository.
* Run `yarn`.
* Create a file called `test.py`.
* Run `yarn prettier test.py` to check the output.
* Run `yarn prettier -- --write test.py` to rewrite file.
* Check out `yarn prettier -- --help` for other options.

## Install

```bash
yarn add --dev --exact prettier @prettier/plugin-python
```

## Use

```bash
prettier --write "**/*.py"
```

## Maintainers

<table>
  <tbody>
    <tr>
      <td align="center">
        <a href="https://github.com/patrick91">
          <img width="150" height="150" src="https://github.com/patrick91.png?v=3&s=150">
          </br>
          Patrick Arminio
        </a>
      </td>
      <td align="center">
        <a href="https://github.com/FuegoFro">
          <img width="150" height="150" src="https://github.com/FuegoFro.png?v=3&s=150">
          </br>
          Danny Weinberg
        </a>
      </td>
      <td align="center">
        <a href="https://github.com/ryanashcraft">
          <img width="150" height="150" src="https://github.com/ryanashcraft.png?v=3&s=150">
          </br>
          Ryan Ashcraft
        </a>
      </td>
    </tr>
  <tbody>
</table>
