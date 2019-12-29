## Introduction
The aim of this repository is to generate an Ubuntu image having Qt installed, either the default Qt coming from Ubuntu main distribution repository or by using [Beineri repositoty](https://launchpad.net/~beineri).

## Branches
This repository contains many branches, each one is using a specific Ubuntu version with a specific Qt one.
The master branch is a template for what a dockerfile should be like either by choosing the default Qt or Beineri one.

| Branch | Docker Tag | Ubuntu | Qt |
|--------|------------|--------|----|
| [default_qt5_bionic](https://github.com/theshadowx/Qt5_Docker/tree/default_qt5_bionic) | default_qt5_bionic, bionic, 18.04, latest | 18.04 (Bionic Beaver) | 5.9.5 |
| [default_qt5_xenial](https://github.com/theshadowx/Qt5_Docker/tree/default_qt5_xenial) | default_qt5_xenial, xenial, 16.04 | 16.04 (Xenial Xerus) | 5.5.1 |
| [default_qt5_trusty](https://github.com/theshadowx/Qt5_Docker/tree/default_qt5_trusty) | default_qt5_trusty, trusty, 14.04 | 14.04 (Trusty Tahr) | 5.2.1 |
| [beineri_qt55_trusty](https://github.com/theshadowx/Qt5_Docker/tree/beineri_qt55_trusty) | beineri_qt55_trusty | 14.04 (Trusty Tahr) | 5.5.1 |
| [beineri_qt55_trusty](https://github.com/theshadowx/Qt5_Docker/tree/beineri_qt56_trusty) | beineri_qt56_trusty | 14.04 (Trusty Tahr) | 5.5.6 |
| [beineri_qt56_xenial](https://github.com/theshadowx/Qt5_Docker/tree/beineri_qt56_xenial) | beineri_qt56_xenial | 16.04 (Trusty Tahr) | 5.6.2 |
