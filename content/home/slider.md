---
widget: slider
headless: true  # This file represents a page section.
weight: 5  # Order that this section will appear.

# ... Put Your Section Options Here (section position etc.) ...

# Slide interval.
# Use `false` to disable animation or enter a time in ms, e.g. `5000` (5s).
interval: 5000

# Minimum slide height.
# Specify a height to ensure a consistent height for each slide.
height: '450px; background-position:center; background-repeat: no-repeat; background-size: cover'


item:
  - title: Hello
    content: 'We are dynamic '
    # Choose `center`, `left`, or `right` alignment.
    align: left
    # Overlay a color or image (optional).
    #   Deactivate an option by commenting out the line, prefixing it with `#`.
    overlay_color: '#555'  # An HTML color value.
    overlay_img: 'slider_fig1.jpg'  # Image path relative to your `assets/media/` folder
    overlay_filter: 0.1  # Darken the image. Value in range 0-1.
    # Call to action button (optional).
    #   Activate the button by specifying a URL and button label below.
    #   Deactivate by commenting out parameters, prefixing lines with `#`.
    cta_label: Scientist at work
    cta_url: 
    cta_icon_pack: 
    cta_icon: 

  - title: ''
    content: 'Scientist at field work'
    align: left
    overlay_color: '#555'
    overlay_img: 'slider_fig1.jpg'
    overlay_filter: 0.15

  - title: ''
    content: 'Lakes from space'
    align: left
    overlay_color: '#555'
    overlay_img: 'slider_fig2.jpg'
    overlay_filter: 0.3

  - title: ''
    content: 'Surface water dynamics'
    align: left
    overlay_color: '#555'
    overlay_img: 'water_2.jpg'
    overlay_filter: 0
---