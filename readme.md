## DMC-NODE-ARTIFACTS

### Description

Installation package for DMC node startup binary files.

**Currently, only Unix environments are supported. We recommend using Ubuntu 18.04 or higher versions.**

### Version Description
- The development version is a version under development and may undergo significant changes. It is not recommended for use in production environments.
- The stable version is a stable version recommended for use in production environments.

### Usage

#### Version Description

##### Stable Version

dmc_v1_1_installer.sh

sha256sum: 

`1c606049d183247b592730c2b946d6c933b0067eb6e45cd9a3f9f47b69ae0461`

##### Development Version

dmc_v1_1_dev_installer.sh

sha256sum: 

`3b3242db304753cac5c9a5ee36ac06f208ae657f874afea6389ebfcc3c826d91`

#### Installation

```bash
sh dmc_v1_1_installer.sh
```

```bash
$ which dmc
> /usr/local/bin/dmc
```

#### Version

```bash
$ dmc 
> Welcome to Chain OS V1.1. Based on fibjs 0.36.0-dev.
```

The prompt message for the DEV version will include the word "dev," for example: V1.1-dev.