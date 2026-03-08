# EvoScan Manuals CDN

Static file hosting for EvoScan manuals and PDFs, served via GitHub Pages to offload bandwidth from WP Engine.

## Structure

Mirror the WordPress site paths exactly:

```
manuals/
wp-content/uploads/simple-file-list/Manuals/
wp-content/uploads/2022/01/
roms/
drivers/
```

## Usage

Files are served via GitHub Pages at:
`https://evoscan.github.io/evoscan-manuals-cdn/`

The WordPress redirect plugin handles transparent redirection from the original URLs.
