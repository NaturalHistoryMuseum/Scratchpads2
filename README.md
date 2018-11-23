Scratchpads 2.x
===============

[![Join the chat at https://gitter.im/scratchpads2/Lobby](https://badges.gitter.im/scratchpads2/Lobby.svg)](https://gitter.im/scratchpads2/Lobby?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

## Overview

Scratchpads are an online virtual research environment for biodiversity,
allowing anyone to share their data and create their own research networks.
Sites are hosted at the Natural History Museum London, and offered freely to
any scientist that completes an online [registration
form](http://get.scratchpads.eu).

Sites can focus on specific taxonomic groups, or the biodiversity of a
biogeographic region, or indeed any aspect of natural history. Scratchpads are
also suitable for societies or for managing and presenting projects. Key
features of Scratchpads (see also Scratchpads feature list) include: tools to
manage biological classifications, bibliography management, media (images,
video and audio), rich taxon pages (with structured descriptions, specimen
records, and distribution data), and character matrices.

Scratchpads support various ways of communicating with site members and
visitors such as blogs, forums, newsletters and a commenting system.

For more information about what scratchpads are, see [http://scratchpads.eu](http://scratchpads.eu)

## Development & Docker

There are a collection of docker images, mostly intended for development. If
you want to self-host a Scratchpad you can try using these, though we recommend
letting the NHM host your Scratchpad with all of the others, unless you have
some very specific requirements.

To get a development scratchpad up and running:

- [Install docker-sync](https://github.com/EugenMayer/docker-sync/wiki/1.-Installation)
- Copy .env.template to .env and set some environment values
- Run `docker-sync start`
- Run `docker-compose up`
- Go to `localhost:8081/install.php` to start the installation process
- This repo will be mounted inside the docker, so you will be able to see any changes in real time (-ish)

If you want to help develop Scratchpads please don't hesitate to get in touch!

## User Support

We offer extensive support to users of the Scratchpads, whether using an NHM
maintained Scratchpad, or a local one. Support should be requested using the
"Issues..." tab which is visible when logged in to a Scratchpad.
