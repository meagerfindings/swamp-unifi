# swamp-unifi

[swamp](https://swamp.club) extension `@mgreten/unifi` — manage a Ubiquiti
UniFi Dream Machine (UDM / UDM Pro / UDM SE) via the legacy Network firewall
API: firewall groups, firewall rules, clients, and networks.

📖 **Extension documentation:** [extensions/models/README.md](extensions/models/README.md)

📦 **Install:** `swamp extension pull @mgreten/unifi`

## Repository layout

This repository is a swamp workspace (its own `.swamp.yaml` repo). The
publishable extension lives under [extensions/models/](extensions/models/).
The rest (`models/`, `vaults/`, `workflows/`) is the author's homelab
configuration kept alongside for end-to-end testing — feel free to ignore
those when reading the extension itself.

## License

MIT — see [extensions/models/LICENSE.txt](extensions/models/LICENSE.txt).
