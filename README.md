# Trilium for YunoHost

> *This package allow you to install etherpad quickly and simply on a YunoHost server.  
If you don't have YunoHost, please see [here](https://yunohost.org/#/install) to know how to install and enjoy it.*

## Overview
Trilium Notes is a hierarchical note taking application with focus on building large personal knowledge bases.

**Shipped version:** 0.46.7

## Screenshots

![](https://raw.githubusercontent.com/wiki/zadam/trilium/images/screenshot.png)

## Demo

* No demo...

## Configuration

You can find a config file for Trilium at this path `/home/yunohost.app/trilium/config.ini`.

## Documentation

 * Official documentation: https://github.com/zadam/trilium/wiki

## YunoHost specific features

#### Multi-users support

Not supported but multi-instance available.

#### Supported architectures

* Works on x86-64b and x86-32b with an [unofficial build](https://unofficial-builds.nodejs.org/) of nodejs 10.
* Not tested on ARM. 

## Limitations

Synchronization doesn't work using domain/path [because of an error with the SSO](https://github.com/YunoHost/issues/issues/1768).
To synchronize with a desktop local app, use instead IP:PORT to bypass the SSO.

## Additionnal informations

Fully tested with the good old package_check for both x86-64b and x86-32b.

## Links

 * Report a bug: https://github.com/maniackcrudelis/trilium_ynh/issues
 * Upstream app repository: https://github.com/zadam/trilium
 * YunoHost website: https://yunohost.org/
