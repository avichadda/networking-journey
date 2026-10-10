# Packets & Progress

**Make Your Own Cloud @ Home.**

A hands-on technical journal about building and operating a private, self-hosted cloud on home hardware.

## Site structure

GitHub Pages publishes from the `docs/` folder on `main`.

- `docs/index.html` — homepage
- `docs/styles.css` — responsive styles
- `docs/favicon.svg` — Packets & Progress browser icon
- `docs/posts/first-steps-content.html` — article content, with the Jekyll permalink `/posts/first-steps`
- `docs/posts/first-steps.html` — backward-compatible redirect from the former `.html` address

## Article URL

Preferred URL:

`https://avichadda.github.io/networking-journey/posts/first-steps`

The article content source includes Jekyll front matter:

```yaml
---
permalink: /posts/first-steps
---
```

GitHub Pages processes this permalink and publishes the article at the clean URL. The former `/posts/first-steps.html` page forwards visitors to the clean URL.

## Favicon

The homepage and article reference `favicon.svg`. It is a small vector icon with the site's dark background, lime “P”, and teal plus mark.

## Configure GitHub Pages

In repository Settings → Pages, select **Deploy from a branch**, branch `main`, folder `/docs`.

## Preview locally

Open `docs/index.html` in a browser. The site is plain HTML/CSS and needs no package installation; the clean permalink itself is created when Jekyll builds the site.

## Editorial focus, accuracy, and privacy

The goal is to help beginners and homelab enthusiasts build their own cloud at home: self-hosted applications and personal services running on hardware they control. Networking is the foundation; compute, storage, backups, DNS, secure remote access, and service management complete the picture.

The project references Omada networking, a Surface Go running Proxmox on node `pve0`, and services involving NAS/Plex, Docker, AdGuard Home, Tailscale, and Home Assistant. Specific IP addresses, VLAN IDs, DNS rewrites, bridge names, backup destinations, and deployment relationships are not assumed unless verified.

Do not commit passwords, API tokens, private keys, recovery keys, or other secrets. Consider whether public IPs and detailed network topology should be omitted from a public repository.
