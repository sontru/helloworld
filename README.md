# helloworld

#### Table of Contents

1. [Overview](#overview)
2. [Module Description - What the module does and why it is useful](#module-description)
3. [Setup - The basics of getting started with helloworld](#setup)
    * [What helloworld affects](#what-helloworld-affects)
    * [Setup requirements](#setup-requirements)
    * [Beginning with helloworld](#beginning-with-helloworld)
4. [Usage - Configuration options and additional functionality](#usage)
5. [Reference - An under-the-hood peek at what the module is doing and how](#reference)
5. [Limitations - OS compatibility, etc.](#limitations)
6. [Development - Guide for contributing to the module](#development)

## Overview

This Hello World Puppet Module was created using the 'puppet module generate sontru-helloworld' command on the Puppet (Master/Enterprise) server.

This module was uploaded here on GitHub after creating a new project called helloworld and performing the following git commands:
```
cd sontru-helloworld/
git init
git add -A
git commit -m "first commit"
git remote add origin git@github.com:sontru/helloworld.git
git remote set-url origin git@github.com:sontru/helloworld.git #might not be necessary
git push -u origin master
```
## Module Description

This helloworld module just simply creates a file sontru-helloworl in the /tmp directory (i.e. /tmp/sontru-helloworld) which has the contents "Hello World from sontru".

## Setup

### What helloworld affects

* A list of files, packages, services, or operations that the module will alter,
  impact, or execute on the system it's installed on.
* This is a great place to stick any warnings.
* Can be in list or paragraph form.

### Setup Requirements **OPTIONAL**

If your module requires anything extra before setting up (pluginsync enabled,
etc.), mention it here.

### Beginning with helloworld

The very basic steps needed for a user to get the module up and running.

If your most recent release breaks compatibility or requires particular steps
for upgrading, you may wish to include an additional section here: Upgrading
(For an example, see http://forge.puppetlabs.com/puppetlabs/firewall).

## Usage

Put the classes, types, and resources for customizing, configuring, and doing
the fancy stuff with your module here.

## Reference

Here, list the classes, types, providers, facts, etc contained in your module.
This section should include all of the under-the-hood workings of your module so
people know what the module is touching on their system but don't need to mess
with things. (We are working on automating this section!)

## Limitations

This is where you list OS compatibility, version compatibility, etc.

## Development

Since your module is awesome, other users will want to play with it. Let them
know what the ground rules for contributing are.

## Release Notes/Contributors/Etc **Optional**

If you aren't using changelog, put your release notes here (though you should
consider using changelog). You may also add any additional sections you feel are
necessary or important to include here. Please use the `## ` header.
