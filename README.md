# Themes

Custom CSS themes for a self-hosted media server suite. Each theme is designed to give a cohesive look and feel across all services.

---

## Included Themes

| Service | Platform | Description |
|---------|----------|-------------|
| **Jellyfin** | Web | Custom theme for the Jellyfin media server web UI |
| **Homarr** | Desktop | Dashboard theme optimized for desktop viewing |
| **Homarr** | Mobile | Dashboard theme optimized for mobile viewing |
| **BookStack** | Web | Theme for the BookStack wiki/documentation platform |
| **Filebrowser Quantum** | Web | Theme for the Filebrowser Quantum file manager |
| **Immich** | Web | Theme for the Immich photo library |

---

## Structure

```
themes/
├── jellyfin/
├── homarr-desktop/
├── homarr-mobile/
├── bookstack/
├── filebrowser-quantum/
└── immich/
```

---

## Usage

### Jellyfin

1. Go to **Dashboard → Branding**
2. Paste the contents of `jellyfin-theme.css` into the **Custom CSS** field
3. Save

### Homarr

1. Go to **Settings → Appearance → Custom CSS**
2. Paste the contents of `homarr-desktop-theme.css` or `homarr-mobile-theme.css`
3. Save

*note that when using the mobile theme, do not set a page title or do | but instead use a logo with the name added to the side of it. That is what I use and what was used for spacing.

> You will need to make a desktop board and a mobile board to apply each one respectively.

### BookStack

1. Go to **Settings → Customization**
2. Paste the contents of `bookstack-theme.css` into the **Custom HTML Head Content** field wrapped in `<style>` tags
3. Save

### Filebrowser Quantum

1. Go to **Settings → Appearance**
2. Paste the contents of `filebrowser-theme.css` into the custom CSS field
3. Save

### Immich

1. Go to **Account Settings → Appearance**
2. Paste the contents of `immich-theme.css` into the custom CSS field
3. Save

---

## External Projects

| Project | Description |
|---------|-------------|
| [Jellyfin](https://github.com/jellyfin/jellyfin) | Open source media server |
| [Homarr](https://github.com/homarr-labs/homarr) | Self-hosted dashboard |
| [BookStack](https://github.com/BookStackApp/BookStack) | Self-hosted wiki and documentation platform |
| [Filebrowser Quantum](https://github.com/gtsteffaniak/filebrowser) | Self-hosted web file manager |
| [Immich](https://github.com/immich-app/immich) | Self-hosted photo library |
