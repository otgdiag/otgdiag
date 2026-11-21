<div align="center">

# Operational Transport Geometry (OTG)

**Diagnosing Multi-Stage Vision Systems via Operational Transport Geometry**

<br>

## &#128279; PROJECT PAGE: [**otgdiag.github.io/otgdiag**](https://otgdiag.github.io/otgdiag/)

[![Open the project page](https://img.shields.io/badge/%E2%96%B6%20OPEN%20THE%20PROJECT%20PAGE-otgdiag.github.io%2Fotgdiag-9c7424?style=for-the-badge&labelColor=252525)](https://otgdiag.github.io/otgdiag/)

</div>

> [!IMPORTANT]
> **You are on the repository, not the project page.** The overview, method, results, figures and BibTeX are all on the project page: **https://otgdiag.github.io/otgdiag/**

---

## About

OTG is a post-hoc framework for diagnosing domain-dependent behaviour in multi-stage vision systems, which it treats as a frozen computation graph. It discovers candidate domains from the system's own representations, matches each input to donors from a reference domain on content descriptors using entropic optimal transport, replaces the states at chosen interfaces with the donor's, and replays the downstream computation. Each interface or group of interfaces is labelled harmless, consequential or undetermined against a tolerance band fixed in advance, and OTG abstains when the evidence cannot decide.

The paper is an anonymous submission under review.

## What is in this repository

This repository holds the source of the project page.

| Path | Contents |
| --- | --- |
| `index.html` | The project page |
| `static/css/` | Stylesheets |
| `static/js/` | Scripts |
| `static/images/` | Figures, favicon and social preview image |
| `static/videos/` | Overview video |

## Viewing the page locally

```bash
git clone https://github.com/otgdiag/otgdiag.git
cd otgdiag
python3 -m http.server 8000
```

Then open `http://localhost:8000/` in a browser.

## Citation

The BibTeX entry is at the bottom of the [project page](https://otgdiag.github.io/otgdiag/#BibTeX).

---

## Acknowledgment

The project page is built on the Academic Project Page Template by Eliahu Horwitz. The template's original README is kept below in full.

---

# Academic Project Page Template

> **Update (September 2025)**: This template has been modernized with better design, SEO, and mobile support. For the original version, see the [original-version branch](https://github.com/eliahuhorwitz/Academic-project-page-template/tree/original-version).

A clean, responsive template for academic project pages.


Example project pages built using this template are:
- https://horwitz.ai/probex
- https://vision.huji.ac.il/probegen
- https://horwitz.ai/mother
- https://horwitz.ai/spectral_detuning
- https://vision.huji.ac.il/ladeda
- https://vision.huji.ac.il/dsire
- https://horwitz.ai/podd
- https://dreamix-video-editing.github.io
- https://horwitz.ai/conffusion
- https://horwitz.ai/3d_ads/
- https://vision.huji.ac.il/ssrl_ad
- https://vision.huji.ac.il/deepsim



## Start using the template
To start using the template click on `Use this Template`.

The template uses html for controlling the content and css for controlling the style. 
To edit the websites contents edit the `index.html` file. It contains different HTML "building blocks", use whichever ones you need and comment out the rest.  

**IMPORTANT!** Make sure to replace the `favicon.ico` under `static/images/` with one of your own, otherwise your favicon is going to be a dreambooth image of me.

## What's New

- Modern, clean design with better mobile support
- Improved SEO with proper meta tags and structured data
- Performance improvements (lazy loading, optimized assets)
- More Works dropdown
- Copy button for BibTeX citations
- Better accessibility

## Components

- Teaser video
- Image carousel
- YouTube video embedding
- Video carousel
- PDF poster viewer
- BibTeX citation

## Customization

The HTML file has TODO comments showing what to replace:

- Paper title, authors, institution, conference
- Links (arXiv, GitHub, etc.)
- Abstract and descriptions  
- Videos, images, and PDFs
- Related works in the dropdown
- Meta tags for SEO and social sharing

### Meta Tags
The template includes meta tags for better search engine visibility and social media sharing. These appear in the `<head>` section and help with:
- Google Scholar indexing
- Social media previews (Twitter, Facebook, LinkedIn)
- Search engine optimization

Create a 1200x630px social preview image at `static/images/social_preview.png`.

## Tips

- Compress images with [TinyPNG](https://tinypng.com)
- Use YouTube for large videos (>10MB)  
- Replace the favicon in `static/images/`
- Works with GitHub Pages

## Acknowledgments
Parts of this project page were adopted from the [Nerfies](https://nerfies.github.io/) page.

## Website License
<a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-sa/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/">Creative Commons Attribution-ShareAlike 4.0 International License</a>.
