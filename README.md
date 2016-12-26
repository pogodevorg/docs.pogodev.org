[![POGODEV](https://github.com/pogodevorg/assets/blob/master/public/img/logo-github.png?raw=true)](https://pogodev.org)

# docs.pogodev.org
[![Build Status](https://travis-ci.org/pogodevorg/docs.pogodev.org.svg?branch=master)](https://travis-ci.org/pogodevorg/docs.pogodev.org) [![Code Climate](https://codeclimate.com/github/pogodevorg/docs.pogodev.org/badges/gpa.svg)](https://codeclimate.com/github/pogodevorg/docs.pogodev.org) [![Issue Count](https://codeclimate.com/github/pogodevorg/docs.pogodev.org/badges/issue_count.svg)](https://codeclimate.com/github/pogodevorg/docs.pogodev.org) [![license](https://img.shields.io/github/license/pogodevorg/docs.pogodev.org.svg?maxAge=2592000?style=flat-square)](https://github.com/pogodevorg/docs.pogodev.org/blob/master/LICENSE.md)

## Table of Contents
* [What is it?](#what-is-it)
* [Installation](#installation)
  * [Requirements](#requirements)
  * [Instructions](#instructions)
* [Documentation](#documentation)
* [Contributing](#contributing)
  * [Core Maintainers](#core-maintainers)
* [Licensing](#licensing)
  * [Third Party Licenses](#third-party-licenses)
* [Credits](#credits)

## What is it?
`docs.pogodev.org` is our open source github pages documentation site backed with Jekyll.

## Installation

### Requirements
- Linux / macOS
- Ruby (> 2.0)

### Instructions
Set up your project in your code directory
```
git clone https://github.com/pogodevorg/docs.pogodev.org.git
cd docs.pogodev.org
```

Install dependencies
```
./bin/setup
```

Run the server and watch for changes in your files
```
./bin/server
```

## Documentation

### Helper scripts

#### Main script
- `gen-all` : Generate everything from the `.proto` files in the `proto` folder. This should be the only script you have to call manually.

```sh
./bin/gen-all
```

#### Sub-scripts (If the `gen-all` script fails, PANIC!)
- proto2yml : Create a `.yml` file out of a `.proto` file

```sh
./bin/proto2yml proto/v0.33.0.proto > _data/api_latest.yml
```

- ymlapi2md : Create default `.md` files for `enums` and `messages` (templates used are in `./templates`)

```sh
./bin/ymlapi2md _data/api_latest.yml
```

- ymlapi2changelog : Create default changelog `.md` files between 2 versions of the API (templates used are in `./templates`)

```sh
./bin/ymlapi2changelog _data/api_0_31_0.yml _data/api_0_33_0.yml
```

## Licensing
[GNU GPL](https://github.com/pogodevorg/docs.pogodev.org/blob/master/LICENSE) v3 or later.

### Third Party Licenses
    None

## Contributing
Currently, you can contribute to this project by:
* Submitting a detailed [issue](https://github.com/pogodevorg/docs.pogodev.org/issues/new).
* [Forking the project](https://github.com/pogodevorg/docs.pogodev.org/fork), and sending a pull request back to for review.

### Core Maintainers

* [![Build Status](https://github.com/hamue.png?size=36) - hamue](https://github.com/hamue)

* [![Build Status](https://github.com/keyphact.png?size=36) - keyphact](https://github.com/keyphact)

* [![Build Status](https://github.com/HatchingEgg.png?size=36) - HatchingEgg](https://github.com/HatchingEgg)

## Credits
    None
