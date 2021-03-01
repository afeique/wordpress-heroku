# [WordPress](https://wordpress.org/) on [Heroku](http://heroku.com)

**Current WordPress Version:** `5.6.2`

## About:
This project is a template for running [WordPress](http://wordpress.org/) on [Heroku](http://www.heroku.com/). It is based on [Bedrock](https://roots.io/bedrock/), a modern WordPress development stack.

This repo was originally forked from [PhilippHeuer/wordpress-heroku](https://github.com/PhilippHeuer/wordpress-heroku) on 2021-03-01.

All `composer.json` dependencies have been updated to the latest versions as of **2021-03-01**.

The Heroku configuration in this project only uses free resources, but you can upgrade them after deployment.

## Table of Contents
- [Getting Started](#gettingstarted)
- [Features](#features)
- [Wiki](https://github.com/afeique/wordpress-heroku/wiki)
- [Changelog](./CHANGELOG.md)

## Getting Started
#### Method 1: One-Click-Deployment (suggested for evaluation)

[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy)

Using this button you can deploy a new instance of WordPress.

All required extensions (MySQL DB) will be deployed automatically.
This also works if you fork your own project to work on your site.

#### Method 2: Deploy using Heroku CLI (suggested for customization)
Plase check out the [deployment page](https://github.com/afeique/wordpress-heroku/wiki/Deployment) in the wiki for a step-by-step guide.

## Features
 - [x] Better folder structure
 - [x] Dependency management with [Composer](http://getcomposer.org)
 - [x] Easy WordPress configuration with environment variables from Heroku
 - [x] Autoloader for mu-plugins (use regular plugins as mu-plugins)
 - [x] Enhanced security (separated web root and secure passwords with [wp-password-bcrypt](https://github.com/roots/wp-password-bcrypt))

## Problems?

If you have problems using your instance of WordPress, you should check the [official documentation](https://codex.wordpress.org/).
If you discover an issue with the deployment process provided by *this repository*, then [open an issue here](https://github.com/afeique/wordpress-heroku/issues/new).

## License

Released under the [MIT license](./LICENSE).
