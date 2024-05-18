# app-page-template

app-page-template is a jekyll theme for GitHub Pages.

You can [preview the theme to see what it looks like](https://honeyluka.github.io/app-page-template/).

## Usage

To use the template:

1. Click ```Use this template``` button above to create your repository.

2. Open your repository ```settings```, enable ```GitHub Pages``` function below. Choose ```master``` branch and ```/docs``` path, click ```Save``` button.

3. It's Done! Now you can open ```https://[your-github-username].github.io/[repository-name]``` to visit your website.

## Customizing

### _config.yml

```yml
# do not modify
theme: jekyll-theme-cayman

# app name
title: 'app-page-tempalte'

# app short dsecription
description: 'A github page template for app'

# umcomment if you need google analytics
# google_analytics: G-NWQY9CVPF7

show_ios_download_btn: true
ios_download_url: 'https://www.apple.com/'
ios_download_btn_title: 'Download from App Store'

show_android_download_btn: true
android_download_url: 'https://www.google.com'
android_download_btn_title: 'Download from Google Play'

show_web_download_btn: true
web_download_url: 'https://www.google.com'
web_download_btn_title: 'Download .dmg'

show_email_link: true
email: 'example@example.com'

show_terms_link: true
terms_link: 'terms'

show_privacy_link: true
privacy_link: 'privacy'

copyright: 'Copyright Group-Leafy. All rights reserved'

show_app_icon: true
app_icon: 'assets/image/icon.png'

show_screenshot: true
screenshots: ['assets/image/screenshot.png', 'assets/image/screenshot.png']
```

### style.scss

```scss
$header-bg-color: #8f68cf !default;
$header-bg-color-secondary: #155799 !default;
$body-link-color: #1e6bb8 !default;
$section-headings-color: #8f68cf !default;
$screenshot-item-width: 300px;
```