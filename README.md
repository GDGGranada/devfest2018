# GDG Devfest Granada 2018

[![Build Status](https://travis-ci.org/GDGGranada/devfest2018.svg?branch=master)](https://travis-ci.org/GDGGranada/devfest2018/)


## Overview

Official website of the GDG Granada DevFest 2018. This conference will take
place the November 16th, 2018.

This is a fork from [GDG-X Hoverboard](https://github.com/gdg-x/hoverboard).

## Getting Started
1. [Fork repository](https://github.com/gdg-x/hoverboard/fork) and clone it locally
2. Setup Environment
   * Install [Node.js (v8.9.4 or above)](https://nodejs.org/en/download/)
   * Instal Firebase CLI: `npm i -g firebase-tools`
3. Create [Firebase account](https://console.firebase.google.com) and login into [Firebase CLI](https://firebase.google.com/docs/cli/): `firebase login`
4. Update [Hoverboard config](/config) and [Resources](/data)
5. Run locally
   * `cd` into the base directory
   * `npm install` or `yarn`
   * `npm run serve` or `yarn serve`
6. Deploy
   * `npm run deploy` or `yarn deploy`

:book: Read the [Full Setup Guide](/docs/).

### Docker-based development environment

If you don't want to bother with the dependencies, you can use the docker container for development.

:book: Read more in [docker docs](/docs/tutorials/docker.md).

## Updating
Here is a git workflow for updating your fork (or downloaded copy) to the latest version:
```
git remote add upstream https://github.com/gdg-x/hoverboard.git
git fetch upstream
git merge upstream/hoverboard-v2
# resolve the merge conflicts in your editor
git add . -u
git commit -m 'Updated to the latest version'
```

## Documentation

The [Getting Started guide](#getting-started) is probably a good first point of call! <br>
:book: [Full documentation](/docs/).

## Compatibility

:white_check_mark: Compatible with **latest two** version of Chrome, Chrome for Android, Firefox, Opera, Safari, Edge.<br>
:x: IE and Opera Mini aren't supported.

## Technology Stack

* Polymer 2
* Firebase
* Service Worker
* CSS Grid

## Contributing

Awesome! Contributions of all kinds are greatly appreciated. To help smoothen the process we have a few non-exhaustive guidelines to follow which should get you going in no time.

### Using GitHub Issues

* Feel free to use GitHub issues for questions, bug reports, and feature requests
* Use the search feature to check for an existing issue
* Include as much information as possible and provide any relevant resources (Eg. screenshots)
* For bug reports ensure you have a reproducible test case
   * A pull request with a breaking test would be super preferable here but isn't required

### Submitting a Pull Request

* Squash commits
* Lint your code with eslint (config provided)
* Include relevant test updates/additions

## Code of Conduct

Read the full version [Code of Conduct](/docs/tutorials/Code-of-Conduct.md).


## License

Project is published under the [MIT license](/LICENSE.md).
Feel free to clone and modify repo as you want, but don't forget to add reference to authors :)

_GDG[x] and GDG Granada are not endorsed and/or supported by Google, the corporation._
