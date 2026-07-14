# eos-redoxer

**E-OS fork of [`redox-os/redoxer`](https://gitlab.redox-os.org/redox-os/redoxer).** Part of the [**E-OS**](https://github.com/Gh0s777tt/E-OS) ecosystem — a hardened, Crimson-branded downstream of [Redox OS](https://www.redox-os.org).

This repository is **Redoxer** — build/run/test Rust programs against Redox.

## E-OS changes vs upstream

_None yet_ — pinned to a clean upstream commit. E-OS branding and config for this component are applied via **recipe patches in the [main repo](https://github.com/Gh0s777tt/E-OS)**, not fork commits.

## How it's pinned

The E-OS build pins this fork in [`recipes/dev/redoxer/recipe.toml`](https://github.com/Gh0s777tt/E-OS/blob/main/recipes/dev/redoxer/recipe.toml):

- branch **`master`** · rev **`a78d6b516ad5`**
- **2 commit(s) behind** upstream master

## Build standalone

This fork is normally built by the E-OS cookbook (`make CI=1 …` in the [main repo](https://github.com/Gh0s777tt/E-OS)). To build it on its own you need the Redox toolchain; see the main repo's [build guide](https://github.com/Gh0s777tt/E-OS/blob/main/docs/building.md).

## Hosting

**GitLab (source of truth):** https://gitlab.com/e-os/eos-redoxer  
**GitHub (read-only mirror):** https://github.com/Gh0s777tt/eos-redoxer

## License

MIT (inherited from upstream Redox). The E-OS project as a whole is AGPL-3.0; see the [main repo](https://github.com/Gh0s777tt/E-OS/blob/main/LICENSE).

---
[E-OS main repo](https://github.com/Gh0s777tt/E-OS) · [Docs](https://github.com/Gh0s777tt/E-OS/tree/main/docs) · [Upstream](https://gitlab.redox-os.org/redox-os/redoxer)
