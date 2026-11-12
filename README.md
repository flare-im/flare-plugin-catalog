# Flare Plugin Catalog

English · [Simplified Chinese](README.zh-CN.md)

Browse public metadata for Flare IM plugins in [plugins.json](plugins.json). Versions identify the source catalog snapshot. Distribution and platform fields describe SDK composition support for that version.

Plugin access and distribution are managed by Flare. For integration contracts and an example manifest, see the [Flare Plugin DevKit](https://github.com/flare-im/flare-plugin-devkit).

The catalog workflow checks the public fields, supported distribution mode, and unique plugin IDs. `plugins.json` is generated from the plugin manifests by the plugin owners' catalog script; when the workflow can read those sources it also checks that every version matches. Build inputs, artifact access, and tenant approval are handled by the plugin owners and the platform.

See the [catalog workflow](.github/workflows/catalog.yml) for the publication checks.
