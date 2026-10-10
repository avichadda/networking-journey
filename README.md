# Packets & Progress

**Make Your Own Cloud @ Home.**

A hands-on technical journal about building and operating a private, self-hosted cloud on home hardware. Topics include networking, Proxmox, storage, backups, Docker, DNS, secure remote access, and home services.

## Site structure

GitHub Pages is intended to publish from the `docs/` folder on `main`.

- `docs/index.html` — homepage and topic directory
- `docs/styles.css` — responsive visual design and article styles
- `docs/posts/first-steps.html` — first article: *Make Your Own Cloud @ Home: Network, Compute, Storage, and Services*

## Preview locally

Open `docs/index.html` in a browser. No build step or package installation is required.

## Configure GitHub Pages

1. Open [repository Pages settings](https://github.com/avichadda/networking-journey/settings/pages).
2. Under **Build and deployment**, choose **Deploy from a branch**.
3. Select branch `main` and folder `/docs`, then save.
4. GitHub will show the published site URL when the Pages deployment is available.

Keep the `docs/posts/` folder and stylesheet in their current relative locations so the links continue to work.

## Editorial focus

The site's main goal is to help beginners and homelab enthusiasts build their own cloud at home: self-hosted applications and personal services running on hardware they control. Networking is the foundation; compute, storage, backups, DNS, secure remote access, and service management complete the picture.

## Technical accuracy and privacy

The articles distinguish known lab components from examples and unconfirmed configuration. The project references Omada networking, a Surface Go running Proxmox on node `pve0`, and services involving NAS/Plex, Docker, AdGuard Home, Tailscale, and Home Assistant. Specific IP addresses, VLAN IDs, DNS rewrites, bridge names, backup destinations, and deployment relationships are not assumed unless verified.

Before publishing technical specifics, verify them against the actual configuration. Do not commit passwords, API tokens, private keys, recovery keys, or other secrets. Consider whether public IPs and detailed network topology should be omitted from a public repository.
