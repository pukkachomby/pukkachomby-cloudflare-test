# Megakit
## Develop
* [Hugo](https://gohugo.io/) `0.87.0`

## Todo
* REDO this whole thing so it can receive updates
    * See the Setup section in Website.md
* Google Analytics
* Facebook Pixel
* Add to CloudFlare
* See Website notes for more
* Clean out pics

## Files
### List of edited files
* NB I try to note changes with `CUSTOM:` marker
* /data/company.yml
    * SEO, should match meta.yml, although SEO section isn't used?
    * navbar
    * logo

| File                                                              | Description                      |
|-------------------------------------------------------------------|----------------------------------|
| /assets/scss/templates/_cta.scss                                  | CTA bg pic path                  |
| /assets/scss/templates/_navigation.scss                           | Topbar vertical line separator   |
| /assets/scss/templates/_pricing.scss                              | Pricing bg pic path              |
| /assets/scss/templates/_slider.csss                               | No edits, but good for homepage  |
| /assets/scss/_variables.scss                                      | Colors                           |
| /component-library/components/map/map.hugo.html                   | Gmap marker icon path            |
| /component-library/components/contact_form/contact_form.hugo.html | Formspree action                 |
| /content                                                          | Fill in                          |
| /data/footer.yml                                                  | Footer                           |
| /data/meta.yml                                                    | SEO!                             |
| /data/nav.yml                                                     | Navbar                           |
| /layouts/_default/baseof.html                                     | Gmaps API, "Zalo" text in topbar |
| /layouts/partials/footer.html                                     | Formspree action                 |
| /layouts/partials/head.html                                       | Favicon, DEPRECATION FIX         |
| /static/images                                                    | Images                           |
| config.toml                                                       | Obvious, DEPRECATION FIX         |

### NERDTreeBookmarks
```
blog ~/Documents/hugo-megakit/content/posts/_index.md
color ~/Documents/hugo-megakit/assets/scss/_variables.scss
config.toml ~/Documents/hugo-megakit/config.toml
contact-form-action ~/Documents/hugo-megakit/component-library/components/contact_form/contact_form.hugo.html
cta-bg-pic ~/Documents/hugo-megakit/assets/scss/templates/_cta.scss
favicon ~/Documents/hugo-megakit/layouts/partials/head.html
footer ~/Documents/hugo-megakit/data/footer.yml
footer.html ~/Documents/hugo-megakit/layouts/partials/footer.html
header-vert-line ~/Documents/hugo-megakit/assets/scss/templates/_navigation.scss
homepage ~/Documents/hugo-megakit/assets/scss/templates/_slider.scss
idkbar ~/Documents/hugo-megakit/data/meta.yml
map-api-LINKEDIN ~/Documents/hugo-megakit/layouts/_default/baseof.html
map-icon ~/Documents/hugo-megakit/component-library/components/map/map.hugo.html
MASTER ~/Documents/hugo-megakit/content/_index.md
navbar ~/Documents/hugo-megakit/data/nav.yml
pricing-bg ~/Documents/hugo-megakit/assets/scss/templates/_pricing.scss
topbar ~/Documents/hugo-megakit/data/company.yml
```
