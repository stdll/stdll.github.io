---
layout: post
title:  "Setting up Nginx and Let's Encrypt"
---

## Prerequisites

* Install Docker and Portainer

## Steps

* Install Nginx

* Get Acme.sh

* Prepare site configuration
  * HTTP only
  * Nginx needs to be able to restart!

* Issue test certificates with Let's Encrypt staging!
  * Don't run into rate limits.
  * If everything works, you can switch to production.

* Issue real certificate & install to Nginx

* Complete configuration

* Make sure renewal works - force it once!

## Next post

* Proxying to a container.

## Sources

* hosting.de Guide (Link!)
* Let's Encrypt documentation (Staging!)
