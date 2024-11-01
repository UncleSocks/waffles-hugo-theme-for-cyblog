![waffles](https://github.com/user-attachments/assets/13f5e303-8376-4464-ab5f-bbd5b4ca6211)

# Waffles: A Hugo Theme for CyBlog 
![Static Badge](https://img.shields.io/badge/Made%20With-Hugo-skyblue)    ![Static Badge](https://img.shields.io/badge/Theme-Minimal%20Dark-black)    ![Static Badge](https://img.shields.io/badge/Status-Under%20Development-pink)

Waffles 🧇 is a minimal and responsive dark Hugo theme created for my CyBlog website. 
The colorway takes inspiration from the cliché "hacking" computer terminal look — a black/grey background with green text. The theme is named after our Shih Tzu, Waffle, or "fifi" for short, and was heavily influenced the Risotto Hugo theme.

![Waffles Screenshot](https://github.com/user-attachments/assets/18826ae0-73c9-4897-b071-5f7b02b2ad17)


## Features

The current theme version only has basic features -- perfect for simple blog posts inspired by hacking or cybersecurity. In addition to blog posting, it supports the following:
- Plain HTML/CSS, no JavaScript and frameworks
- Responsive to different screen sizes, including mobile phones.
- Favicons support (Font Awesome)
- Tags support
- About page

## Installation 
After creating your Hugo site, download or Git Clone this repository and copy the directory to the site's `themes` directory using the following command:

```
git clone https://github.com/UncleSocks/waffles-hugo-theme-for-cyblog  themes/waffles
```

### Configuration
Then, configure the Hugo site to use the Waffles theme by adding `theme = 'waffles'` to the `hugo.toml` file or `theme: waffles` to the `hugo.yaml` file.

## Theme Modification
In addition to the listed features above, you can modify the theme's menu, site's title, description, and copyright on the `hugo.toml` or `hugo.yaml` file. A sample site is available in the `exampleSite` directory for reference.

## Performance
### Home Page
At the time of writing, my CyBlog homepage with the Waffles theme scored **99%** when tested using Lighthouse Desktop (Navigation). It then scored **98%** on mobile devices.

![Waffles Lighthouse Performance](https://github.com/user-attachments/assets/bc2b7b17-4a24-4299-b484-024f01e60588)

