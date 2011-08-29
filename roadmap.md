---
title: Roadmap
layout: default
---

## Roadmap

### v0.1.0

- File structure is defined
- Major dependencies are in place
- Basic plugin and theme system
- Basic CLI installer

The first release will just be a basic application with the core structure in place. It will not be a very useful project manager but will help other developers understand the technologies used and the direction Hyla is heading in.

### v0.2.0

- OAuth API

This release will focus on creating an OAuth provider and switching the web facing controllers to using the API. This is crucial before many plugins are written because the API is where all the core functionality will be placed. The API is an important step to making sure the web application is decoupled from the back-end technologies.

### v0.3.0

- Site settings
- Project settings

The application should start becoming useful at this point. The settings pages will help developers understand the conventions for saving configs into CouchDB documents as well as giving users some needed customization options.

### v0.4.0

- Tracker plugin

We can start focusing on useful features now and putting a lot more polish on the Tracker will allow us to [eat our own dog food](http://www.codinghorror.com/blog/2009/01/the-ultimate-dogfooding-story.html). Hyla will already have a tracker plugin by this release but polishing it will help us find limitations in the plugin system before it's too late.