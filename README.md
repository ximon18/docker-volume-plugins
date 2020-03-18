Origin and credits
==================

This repository: 
- is a blessed fork of https://github.com/trajano/docker-volume-plugins (thankyou [@trajano](https://github.com/trajano/docker-volume-plugins/pull/30#issuecomment-600286395)).
- continues the awesome work done by @trajano as, at present, @trajano hasn't been able to find time to maintain the original project.
- is limited, for now, to just the GlusterFS volume plugin.
- was created initially to fix issue https://github.com/trajano/docker-volume-plugins/issues/29.

Docker Managed Volume Plugins
=============================

This project provide a managed volume plugin for Docker to connect to *existing* [GlusterFS](https://github.com/trajano/docker-volume-plugins/tree/master/glusterfs-volume-plugin) volumes.

As stated in the original project:

> **There is no robust error handling.  So garbage in -> garbage out**