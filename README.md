<!-- markdownlint-configure-file {
  "MD013": false,
  "MD033": false,
  "MD041": false
} -->

<div align="center">

# Home Lab

Self-hosted infrastructure to  **automate** and **simplify** my life.

Trading effort and an increased energy bill for privacy and learning
opportunities :neckbeard:

---

[Content](#content) •
[ToDo](#todo)

---

</div>

## Content

This repository provides:

- `docker-compose` stacks to set up all the self-hosted services I use
- `dockerfiles` for services that don't have official images available
- a package registry for the images built using these `dockerfiles`
- additional configuration files for services that need them

The services are primarily configured using environment variables and managed
using a central [`Portainer`](https://www.portainer.io/) instance with agents
on all the devices/servers I run.

## ToDo

- [ ] Add scripts to (re-)build all images
- [ ] Add scripts to automate the initial setup
- [ ] Explore (or create) alternatives to `Portainer` for something
      less-interactive and more automated
- [ ] Manage secrets
