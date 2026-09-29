# RANN Ultra Searcher: downloads

Downloads of **RANN Ultra Searcher** by RANN APPS: search live folders and the catalog of every drive you have
scanned, even unplugged ones, by name, content, metadata, similar images, faces and objects. On Windows, get the app
from the Microsoft Store; this page has the Linux packages and the **Team server**, which lets a family or a small team
search each other's scans.

> No release has been published yet. The files will appear under **Releases** when version 1 is ready.

Product page and user manual: https://www.rann.ca/rann-apps/rann-ultra-searcher

## The app on Linux

| System | Package | Install |
| --- | --- | --- |
| Ubuntu 24.04 or later, Debian 12 or later, Linux Mint 22 or later | `rann-ultra-searcher_<version>-1_amd64.deb` | `sudo apt install ./rann-ultra-searcher_<version>-1_amd64.deb` |
| Fedora 42 or later | `rann-ultra-searcher-<version>-1.x86_64.rpm` | `sudo dnf install ./rann-ultra-searcher-<version>-1.x86_64.rpm` |

The package manager also installs what the app needs from your system: the Tesseract 5 library (reading text in
pictures), and VLC when available (playing audio and video in the preview). **Ubuntu 22.04 is not supported**: it only
has Tesseract 4, and apt refuses the package ("held broken packages").

After installing, start **RANN Ultra Searcher** from the applications menu, or run `rann-ultra-searcher`. To remove
it: `sudo apt remove rann-ultra-searcher` or `sudo dnf remove rann-ultra-searcher`. Your catalog and settings stay in
`~/.local/share/RANN/UltraSearcher`.

## The Team server

Only one computer on a team needs it. The manual's chapter 8 explains setting it up.

| Where | Download |
| --- | --- |
| A Windows PC | `rann-team-server-<version>-windows-x64.zip` (self-contained: nothing else to install) |
| A Linux PC or server | Already in the Linux package above: `rann-team-server` (at `/opt/rann-ultra-searcher/Rann.Server`) |
| A NAS or server with Docker (x64) | `rann-team-server-<version>-docker.zip`: the server ready-built, with a `Dockerfile` and a `docker-compose.yml` that run it with PostgreSQL and pgvector |

## En français

Téléchargements de RANN Ultra Searcher : les paquets Linux de l'application et le serveur d'équipe pour Windows,
Linux et Docker. Sous Windows, l'application s'obtient dans le Microsoft Store. Le guide d'utilisation, en français,
est à https://www.rann.ca/rann-apps/rann-ultra-searcher.

## Contact

RANN APPS, info-rann-apps@NorthMail.ca
