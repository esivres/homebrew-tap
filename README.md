# esivres Homebrew tap

Homebrew casks for [esivres](https://github.com/esivres) tools. Linux only
(Homebrew on Linux).

## o3ui

OpenVPN3 controller: Bubble Tea TUI, Cinnamon desklet and status CLI, driven
by [openvpn3-linux](https://github.com/OpenVPN/openvpn3-linux) over D-Bus.

```sh
brew tap esivres/tap
brew install --cask o3ui
o3ui desklet install   # optional: add the Cinnamon desklet
```

Requires `openvpn3-linux` installed and running on the host — it is a system
package, not a Homebrew formula. A Secret Service daemon (gnome-keyring,
KWallet, …) is needed for stored credentials.

Casks are published automatically by GoReleaser on every
[o3ui release](https://github.com/esivres/o3ui/releases).
