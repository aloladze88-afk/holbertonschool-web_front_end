# Advanced CSS

Holberton School Advanced CSS project.

## Repository

- GitHub repository: `holbertonschool-web_front_end`
- Directory: `CSS_advanced`

## Files and folders

```text
CSS_advanced/
├── README.md
├── index.html
├── index-starter.html
├── UNSPLASH_SOURCES.md
├── images/
│   ├── favicon.jpg
│   ├── logo-black.png
│   ├── logo-white.png
│   ├── pic-about-01.jpg
│   ├── pic-work-01.jpg
│   ├── pic-work-02.jpg
│   ├── pic-work-03.jpg
│   ├── pic-article-01.jpg
│   ├── pic-article-02.jpg
│   ├── pic-article-03.jpg
│   ├── pic-person-01.jpg
│   ├── pic-person-02.jpg
│   └── pic-person-03.jpg
├── scripts/
│   ├── download_unsplash_images.py
│   └── download_unsplash_images.sh
└── styles/
    ├── 1-style.css
    ├── 2-style.css
    ├── ...
    └── 32-style.css
```

## How to use

`index-starter.html` is the starter HTML extracted from the project page. It keeps the original stylesheet placeholder:

```html
<link rel='stylesheet' href='#'>
```

`index.html` is the practical preview file. It links to the final stylesheet:

```html
<link rel="stylesheet" href="styles/32-style.css">
```

To preview earlier tasks, temporarily change the stylesheet link in `index.html`, for example:

```html
<link rel="stylesheet" href="styles/12-style.css">
```

## Download the Unsplash images

The image files already exist as placeholders so the structure is complete. To overwrite them with the selected Unsplash photos, run this from the `CSS_advanced` folder:

```bash
python3 scripts/download_unsplash_images.py
```

or:

```bash
bash scripts/download_unsplash_images.sh
```

## Notes

The ten `pic-*` images are selected from Unsplash and mapped in `UNSPLASH_SOURCES.md`. The two logos and favicon are simple local project assets, not Unsplash photos.
