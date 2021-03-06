---
layout: concertina
distro: GNU Guix
icon: guix.png
homepage: https://www.gnu.org/software/guix/packages/n.html#neomutt
title: NeoMutt for GNU Guix
maintainer: The GNU Guix team
---

# ![logo](/images/distros/{{page.icon}}) {{ page.title }}

## Installation <a class="offset" id="install"></a>

To install neomutt into your profile, run

```
guix package --install neomutt
```

## Update <a class="offset" id="update"></a>

To upgrade just neomutt in your profile, run

```
guix package --upgrade neomutt
```

## Uninstall <a class="offset" id="uninstall"></a>

To remove neomutt from your profile, run

```
guix package --remove neomutt
```

## From git <a class="offset" id="dev-build"></a>

To build neomutt from the HEAD of the neomutt sources,
you can use the contrib/guix-neomutt.scm file with any
of the relevant guix commands. For example

```
cd contrib
guix package --install-from-file=contrib/guix-neomutt.scm
```

for installation,

```
guix build --install-from-file=contrib/guix-neomutt.scm
```

for building it.

Read the [GNU Guix Reference Manual](https://www.gnu.org/software/guix/manual/guix.html) for more information
and examples on usage.