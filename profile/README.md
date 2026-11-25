<p align="center"><img src="https://raw.githubusercontent.com/hobnix/core/main/.github/branding/banner@2x.webp" alt="hobnix" width="100%"></p>

# Hobnix

A NixOS home server you can read: apps in Incus containers, shares, backups, a web interface and one command, `hs`, to run it all.
Status: beta. Steps that were not run on real hardware are marked "Not tested on hardware yet." in the guides.

| Repository | What it is |
| --- | --- |
| [core](https://github.com/hobnix/core) | The framework: the `hs` command, the web interface, the installer and the package client |
| [official](https://github.com/hobnix/official) | Packages the project maintains: apps, optional parts, capabilities and blueprints, in a signed index |
| [community](https://github.com/hobnix/community) | Packages from other people, reviewed, with a lower trust tier |

Apps and optional parts reach a server with `hs pkg`; a blueprint chooses a ready-made set at install time. Other repositories can be added
with `hs pkg repo add`. The older repositories `recipes`, `extensions` and `capabilities` are retired into `official`.

**Install:** [install guide](https://github.com/hobnix/core/blob/main/docs/install.md).
**Docs:** the guides are in the [docs folder of core](https://github.com/hobnix/core/tree/main/docs) and start with the [overview](https://github.com/hobnix/core#readme).
