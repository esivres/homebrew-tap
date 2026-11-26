# esivres Homebrew tap

Homebrew packaging for [esivres](https://github.com/esivres) tools.

```sh
brew tap esivres/tap
```

## o3ui

OpenVPN3 controller: Bubble Tea TUI, Cinnamon desklet and status CLI, driven
by [openvpn3-linux](https://github.com/OpenVPN/openvpn3-linux) over D-Bus.

```sh
brew install --cask o3ui
o3ui desklet install   # optional: add the Cinnamon desklet
```

Linux only. Requires `openvpn3-linux` installed and running (a system package,
not a Homebrew formula) and a Secret Service daemon (gnome-keyring, KWallet, …)
for stored credentials.

## mmcli

Console Mattermost client for automation.

```sh
brew install --cask mmcli
```

On Linux the name `mmcli` is taken by ModemManager (`/usr/bin/mmcli`); call
`$(brew --prefix)/bin/mmcli` in scripts.

## mdrev

Review markdown documents — inline comments, questions and suggested edits.

```sh
brew install mdrev
```

macOS and Linux. Windows users install through the
[scoop bucket](https://github.com/esivres/mdrev).

Casks and formulas are published automatically by GoReleaser on every release.
