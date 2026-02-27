# MeowCatHugoTheme

A Hugo theme.

## ⚠️ Work in Progress

This Hugo theme is under active development and is not yet production-ready.
Expect frequent updates and potential breaking changes.

## Features

- Multilingual support (English, Turkish, Arabic with RTL)
- Dark/Light mode
- Reading time
- Author bio
- Social sharing
- Newsletter subscription
- Responsive design
- Code syntax highlighting

## Quick Start

### 1. Create a new Hugo site

```bash
hugo new site myblog
cd myblog
```

### 2. Install the theme

```bash
git clone https://github.com/MamunAlshawa/MeowCatHugoTheme.git themes/MeowCatHugoTheme
```

### 3. Copy the example config

Copy `themes/MeowCatHugoTheme/config.yaml` to your site's root directory and customize:

```yaml
baseURL: "https://example.com"
languageCode: "en-us"
title: "My Blog"
theme: MeowCatHugoTheme

# Customize your social links
social:
  twitter: "https://x.com/yourhandle"
  github: "https://github.com/yourhandle"
  instagram: "https://instagram.com/yourhandle"
  linkedin: "https://linkedin.com/in/yourhandle"
  youtube: "https://youtube.com/@yourhandle"
  dribbble: "https://dribbble.com/yourhandle"
```

### 4. Run the server

```bash
hugo server -D
```

Visit `http://localhost:1313` to see your site.

## Configuration

All Hugo settings are defined in the theme's config.yaml. Override only what you need in your site's config.yaml.

### Languages

The theme supports multiple languages:

- English (default)
- Turkish (Türkçe)
- Arabic (العربية) - RTL support

### Taxonomies

- Tags
- Categories
- Series

### Single Author

This theme supports a single author with a dedicated author page showing:

- Author avatar and bio
- Social media links
- List of all articles by the author

## License

MIT License - See LICENSE file for details.

## Credits

Original theme by [GitHub](https://github.com/forestryio/hugo-theme-novela)
