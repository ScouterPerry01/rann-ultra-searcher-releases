# RANN Ultra Searcher for Linux

Linux packages of **RANN Ultra Searcher** by RANN APPS: search live folders and the catalog of every drive you have
scanned, even unplugged ones, by name, content, metadata, similar images, faces and objects. Each package also holds
the **Team server**, which shares catalogs between people.

> No release has been published yet. The packages will appear under **Releases** when version 1 is ready.

## Which package

| System | Package | Install |
| --- | --- | --- |
| Ubuntu 24.04 or later, Debian 12 or later, Linux Mint 22 or later | `rann-ultra-searcher_<version>-1_amd64.deb` | `sudo apt install ./rann-ultra-searcher_<version>-1_amd64.deb` |
| Fedora 42 or later | `rann-ultra-searcher-<version>-1.x86_64.rpm` | `sudo dnf install ./rann-ultra-searcher-<version>-1.x86_64.rpm` |

The package manager also installs what the app needs from your system: the Tesseract 5 library (reading text in
pictures), and VLC when available (playing audio and video in the preview). **Ubuntu 22.04 is not supported**: it only
has Tesseract 4, and apt refuses the package ("held broken packages").

After installing, start **RANN Ultra Searcher** from the applications menu, or run `rann-ultra-searcher`.

## The Team server

The server is installed with the app, at `/opt/rann-ultra-searcher/server/Rann.Server` (also `rann-team-server`), but
it doesn't run until you set it up and install it as a service. Run `rann-team-server` for its commands.

## Removing

`sudo apt remove rann-ultra-searcher` or `sudo dnf remove rann-ultra-searcher`. Your catalog and settings stay in
`~/.local/share/RANN/UltraSearcher`.

## Contact

RANN APPS, info-rann-apps@NorthMail.ca
