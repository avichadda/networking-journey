# Packets & Progress

**Practical networking, one layer at a time.**

A hands-on technical journal covering home networking, Proxmox, Docker, DNS, remote access, and self-hosted services. The site is a small static website built with plain HTML and CSS.

## Site structure

- `index.html` — the homepage and topic directory
- `styles.css` — responsive visual design and article styles
- `posts/first-steps.html` — first article: *Building a Small Homelab: Network, Compute, and Services*

## Preview locally

Download or clone this repository, then open `index.html` in a browser. There is no build step or package installation required.

## Publish with GitHub Pages

1. Open the repository's **Settings** tab.
2. Select **Pages** in the sidebar.
3. Under the build/deployment configuration, select **Deploy from a branch** if that option is available.
4. Choose branch `main` and folder `/(root)`, then save.
5. Wait for the deployment to complete; GitHub Pages will show the published site URL in the Pages settings.

The repository needs to contain the homepage at the root. Keep the `posts/` folder and stylesheet in their current relative locations.

## Technical accuracy and privacy

The articles are intended to distinguish verified settings from examples and unconfirmed details. The first article references the identified Omada equipment, a Surface Go running Proxmox on node `pve0`, and services involving Docker, AdGuard Home, Tailscale, and Home Assistant. Specific IP addresses, VLAN IDs, DNS rewrites, bridge names, and deployment relationships are not assumed.

Before publishing further technical specifics, verify them against the actual configuration. Do not commit passwords, API tokens, private keys, recovery keys, or other secrets. Consider whether public IPs and detailed network topology should be omitted from public posts.
