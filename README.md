# EvoScan Manuals CDN

Static file hosting for EvoScan manuals and PDFs, served via GitHub Pages to offload bandwidth from WP Engine.

## Structure

Mirror the WordPress site paths exactly:

```
manuals/
wp-content/uploads/simple-file-list/Manuals/
wp-content/uploads/2022/01/
wp-content/uploads/2022/02/
wp-content/uploads/pdf-previews/
roms/
drivers/
```

## Usage

Files are served via GitHub Pages at:
`https://evoscan.github.io/evoscan-manuals/`

The WordPress redirect plugin handles transparent redirection from the original URLs.

## PDF Preview Images

Static PNG previews (first page of each PDF) are stored in `wp-content/uploads/pdf-previews/` and used on the tech-articles page in place of inline PDF embeds.
