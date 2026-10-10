# Packets & Progress

**Practical networking, one layer at a time.**

A hands-on technical journal covering home networking, Proxmox, Docker, DNS, remote access, and self-hosted services. The website is a static site built with HTML and CSS.

## Site structure

GitHub Pages is intended to publish from the `docs/` folder on `main`.

- `docs/index.html` — homepage and topic directory
- `docs/styles.css` — responsive visual design and article styles
- `docs/posts/first-steps.html` — first article: *Building a Small Homelab: Network, Compute, and Services*

## Preview locally

Open `docs/index.html` in a browser. No build step or package installation is required.

## Configure GitHub Pages

1. Open [repository Pages settings](https://github.com/avichadda/networking-journey/settings/pages).
2. Under **Build and deployment**, choose **Deploy from a branch**.
3. Select branch `main` and folder `/docs`, then save.
4. GitHub will show the published site URL when the Pages deployment is available.

Keep the `docs/posts/` folder and stylesheet in their current relative locations so the links continue to work.

## Technical accuracy and privacy

The articles distinguish verified details from examples and unconfirmed configuration. The first article references the identified Omada equipment, a Surface Go running Proxmox on node `pve0`, and services involving Docker, AdGuard Home, Tailscale, and Home Assistant. Specific IP addresses, VLAN IDs, DNS rewrites, bridge names, and deployment relationships are not assumed.

Before publishing more technical specifics, verify them against the actual configuration. Do not commit passwords, API tokens, private keys, recovery keys, or other secrets. Consider whether public IPs and detailed network topology should be omitted from public posts.
