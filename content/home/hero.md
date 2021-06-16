---
active: true
widget: hero
headless: true  # This file represents a page section.
weight: 5 # Order that this section appears on the page.
height: 300px
design:
  background:
    # Name of image in `assets/media/`.
    image: cover_img.jpg
    # Darken the image? Range 0-1 where 0 is transparent and 1 is opaque.
    image_darken: 0.6
    #  Options are `cover` (default), `contain`, or `actual` size.
    image_size: cover
    # Options include `left`, `center` (default), or `right`.
    image_position: center
    # Use a fun parallax-like fixed background effect on desktop? true/false
    image_parallax: true
    # Text color (true=light, false=dark, or remove for the dynamic theme color).
    text_color_light: true

# ... Put Your Section Options Here (title etc.) ...

# Hero image (optional). Enter filename of an image in the assets/media/ folder.
#hero_media: 'cover_img.jpg'

# Call to action links (optional).
#   Display link(s) by specifying a URL and label below. Icon is optional for `cta`.
#   Remove a link/note by deleting a cta/note block.
cta:
  url: 'https://wowchemy.com'
  label: Get Started
  icon_pack: fas
  icon: download
cta_alt:
  url: 'https://wowchemy.com'
  label: View Documentation

# Note. An optional note to show underneath the links.
cta_note:
  label: ''
---