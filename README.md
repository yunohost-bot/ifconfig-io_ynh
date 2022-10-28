<!--
N.B.: This README was automatically generated by https://github.com/YunoHost/apps/tree/master/tools/README-generator
It shall NOT be edited by hand.
-->

# ifconfig-io for YunoHost

[![Integration level](https://dash.yunohost.org/integration/ifconfig-io.svg)](https://dash.yunohost.org/appci/app/ifconfig-io) ![Working status](https://ci-apps.yunohost.org/ci/badges/ifconfig-io.status.svg) ![Maintenance status](https://ci-apps.yunohost.org/ci/badges/ifconfig-io.maintain.svg)  
[![Install ifconfig-io with YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=ifconfig-io)

*[Lire ce readme en français.](./README_fr.md)*

> *This package allows you to install ifconfig-io quickly and simply on a YunoHost server.
If you don't have YunoHost, please consult [the guide](https://yunohost.org/#/install) to learn how to install it.*

## Overview

Inspired by ifconfig.me, but designed for pure speed. A single server can do 18,000 requests per seconds while only consuming 50megs of ram.

I used the gin framework as it does several things to ensure that there are no memory allocations on each request, keeping the GC happy and preventing unnessary allocations.

Tested to handle 15,000 requests persecond on modest hardware with an average response time of 130ms.


**Shipped version:** 2022.10.21~ynh1

**Demo:** https://ifconfig.io
## Documentation and resources

* Official app website: <https://ifconfig.io/>
* Official user documentation: <https://github.com/georgyo/ifconfig.io/>
* Official admin documentation: <https://github.com/georgyo/ifconfig.io/>
* Upstream app code repository: <https://github.com/georgyo/ifconfig.io/>
* YunoHost documentation for this app: <https://yunohost.org/app_ifconfig-io>
* Report a bug: <https://github.com/YunoHost-Apps/ifconfig-io_ynh/issues>

## Developer info

Please send your pull request to the [testing branch](https://github.com/YunoHost-Apps/ifconfig-io_ynh/tree/testing).

To try the testing branch, please proceed like that.

``` bash
sudo yunohost app install https://github.com/YunoHost-Apps/ifconfig-io_ynh/tree/testing --debug
or
sudo yunohost app upgrade ifconfig-io -u https://github.com/YunoHost-Apps/ifconfig-io_ynh/tree/testing --debug
```

**More info regarding app packaging:** <https://yunohost.org/packaging_apps>
