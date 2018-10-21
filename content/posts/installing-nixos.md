+++
title = "Installing NixOS"
date = "2018-10-21T13:26:28-05:00"
type = "post"
description = "My journey installing NixOS on an HP Spectre x360"
image = "img/posts/nixos-logo.png"
github = "gvacaliuc/"
tags = ["nix", "nixos", "linux"]
draft = false
+++

## Installing NixOS

I'm going to use this post to catalog my journey installing NixOS.  It aims to
be be useful to anyone attempting to do the same / myself in the future.

A bit of background on [NixOS](https://nixos.org):  

* operating system designed around a declarative, functional package manager
  ([nix](https://nixos.org/nix/)) 
* system upgrades / downgrades can be rolled back as they are described and
  referenced by a single hash
* declarative system configuration = define your system in a declarative PL
  rather than bash commands spread out over several years


### getting started

1. backup all your data
2. get a live usb of the [latest nix
   iso](https://nixos.org/nixos/download.html)

Once you've got all that setup 
