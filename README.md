![eza for Debian](.github/readme-header.png)

# eza for Debian

[eza](https://github.com/eza-community/eza) — a modern, maintained replacement
for `ls` — packaged for Debian as part of
[latest-debs](https://github.com/latest-debs).

## Install

Via the latest-debs apt repository:

```sh
sudo extrepo enable latest-debs
sudo apt update
sudo apt install eza
```

Or download a `.deb` from the [Releases](https://github.com/latest-debs/eza-debian/releases) page:

```sh
sudo dpkg -i eza_*.deb
```

## Supported distributions & architectures

- Debian Bookworm (12), Trixie (13), Forky (14/testing), Sid (unstable)
- amd64, arm64, armhf

  (eza's upstream releases only publish amd64/arm64/armhf Linux binaries)

## Collaborate with us

latest-debs is a community effort. If you rely on this package and want to
help keep it fresh, watching for a new upstream release or fixing a build
hiccup, we'd love your help. Open an issue on this repo, or email
**latest-debs@users.noreply.github.com** to get involved.

## Disclaimer

Unofficial packaging only. For issues with eza itself, see
[eza-community/eza](https://github.com/eza-community/eza).
