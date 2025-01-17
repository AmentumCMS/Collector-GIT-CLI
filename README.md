# What is this?

[![Release](https://github.com/amentumcms/Collector-k9s-CLI/actions/workflows/collect.yml/badge.svg?branch=main)](https://github.com/amentumcms/Collector-k9s-CLI-IB/actions/workflows/collect.yml)

This is a project that automatically collects artifacts to ease in air-gapped transfer from the internet.

It runs actions manually or on Push and creates a release.

In this case, it collects the source code repositories and the associated container images via skopeo & gh for:

- Docker Hub k9s CLI Container image
- Git Hub k9s CLI latest release artifacts 
