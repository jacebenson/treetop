+++
# Slider widget.
widget = "slider"  # See https://sourcethemes.com/academic/docs/page-builder/
headless = true  # This file represents a page section.
active = true  # Activate this widget? true/false
weight = 1  # Order that this section will appear.

# Slide interval.
# Use `false` to disable animation or enter a time in ms, e.g. `5000` (5s).
interval = 5000

# Slide height (optional).
# E.g. `500px` for 500 pixels or `calc(100vh - 70px)` for full screen.
height = "calc(100vh - 70px)"

# Slides.
# Duplicate an `[[item]]` block to add more slides.
[[item]]
  title = "Hello"
  content = "I am a simple box"
  align = "center"  # Choose `center`, `left`, or `right`.

  # Overlay a color or image (optional).
  #   Deactivate an option by commenting out the line, prefixing it with `#`.
  overlay_color = "#666"  # An HTML color value.
  overlay_img = "slider/treetop-closed.jpeg"  # Image path relative to your `static/img/` folder.
  overlay_filter = 0.5  # Darken the image. Value in range 0-1.

  # Call to action button (optional).
  #   Activate the button by specifying a URL and button label below.
  #   Deactivate by commenting out parameters, prefixing lines with `#`.
  cta_label = "Get Academic"
  cta_url = "https://sourcethemes.com/academic/"
  cta_icon_pack = "fas"
  cta_icon = "graduation-cap"

[[item]]
  title = "Hand-crafted wooden design"
  content = "I'm handmade with the finest quality wood."
  align = "left"

  overlay_color = "#555"  # An HTML color value.
  overlay_img = "/slider/wooden-hinge-back-left.jpeg"  # Image path relative to your `static/img/` folder.
  overlay_filter = 0.5  # Darken the image. Value in range 0-1.

[[item]]
  title = "Wooden hinges"
  content = "Nearly 100% wood, even my hinges."
  align = "right"

  overlay_color = "#333"  # An HTML color value.
  overlay_img = "/slider/wooden-hinge-back-right.jpeg"  # Image path relative to your `static/img/` folder.
  overlay_filter = 0.5  # Darken the image. Value in range 0-1.

[[item]]
  title = "Custom design for snug plugs"
  content = "These holes are made precisely for a snug fit."
  align = "top"
  overlay_color = "#333"
  overlay_img = "/slider/the-plugs.jpeg"
  overlay_filter = 0.5

[[item]]
  title = "Official parts only"
  content = "I have the official 7 inch Raspberry Pi display."
  align = "top"
  overlay_color = "#333"
  overlay_img = "/slider/the-display.jpeg"
  overlay_filter = 0.5

[[item]]
  title = "Prototyping is my purpose"
  content = "What's yours?"
  alighn = "top"
  overlay_color = "#333"
  overlay_img = "/slider/the-hood.jpeg"
  overlay_filter = 0.5

[[item]]
  title = "Find out more"
  content = "below"
  align = "top"
  overlay_color = "#333"
  overlay_img = "/slider/treetop-open.jpeg"
  overlay_filter = 0.5

+++
