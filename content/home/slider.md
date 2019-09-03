+++
# Slider widget.
widget = "slider"  # See https://sourcethemes.com/academic/docs/page-builder/
headless = true  # This file represents a page section.
active = true  # Activate this widget? true/false
weight = 1  # Order that this section will appear.

[design.spacing]
  # Customize the section spacing. Order is top, right, bottom, left.
  padding = ["0px", "400px", "0px", "400px"]

# Slide interval.
# Use `false` to disable animation or enter a time in ms, e.g. `5000` (5s).
interval = false

# Slide height (optional).
# E.g. `500px` for 500 pixels or `calc(100vh - 70px)` for full screen.
height = "1000px"

# Slides.
# Duplicate an `[[item]]` block to add more slides.
[[item]]
  title = "Art Work"
  content = ""
  align = "right"  # Choose `center`, `left`, or `right`.

  # Overlay a color or image (optional).
  #   Deactivate an option by commenting out the line, prefixing it with `#`.
  # overlay_color = "#555"  # An HTML color value.
  overlay_img = "AMELIORATE.jpeg"  # Image path relative to your `static/img/` folder.
  # overlay_filter = 0.5

[[item]]
  title = ""
  content = ""
  align = "center"

  # overlay_color = "#555"  # An HTML color value.
  overlay_img = "CHAOS.jpeg"  # Image path relative to your `static/img/` folder.
  # overlay_filter = 0.5  # Darken the image. Value in range 0-1.

[[item]]
  title = ""
  content = ""
  align = "center"

  # overlay_color = "#333"  # An HTML color value.
  overlay_img = "DRAMA FREE.jpeg"  # Image path relative to your `static/img/` folder.
  # overlay_filter = 0.5  # Darken the image. Value in range 0-1.
+++
