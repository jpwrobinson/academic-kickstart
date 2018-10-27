+++
# Hero Carousel widget.
widget = "hero_carousel"
active = true
date = 2017-10-15T00:00:00

# Order that this section will appear in.
weight = 1

# Slide interval.
# Use `false` to disable animation or enter a time in ms, e.g. `5000` (5s).
interval = 3000

# Minimum slide height.
# Specify a height to ensure a consistent height for each slide.
height = "300px"

# Slides.
# Duplicate an `[[item]]` block to add more slides.
  # Overlay a color or image (optional).
  #   Deactivate an option by commenting out the line, prefixing it with `#`.
  overlay_color = "#666"  # An HTML color value.
  overlay_img = ""  # Image path relative to your `static/img/` folder.

  # Call to action button (optional).
  #   Activate the button by specifying a URL and button label below.
  #   Deactivate by commenting out parameters, prefixing lines with `#`.
[[item]]
  title = "Coral reefs"
  content = ""
  align = "left"

  overlay_color = "#555"  # An HTML color value.
  overlay_img = "headers/KI_underwater.jpg"  # Image path relative to your `static/img/` folder.

[[item]]
  title = "Fisheries"
  content = ""
  align = "right"

  overlay_color = "#333"  # An HTML color value.
  overlay_img = "headers/SEY_catch.jpg"  # Image path relative to your `static/img/` folder.

[[item]]
  title = "Climate change"
  content = ""
  align = "right"  # Choose `center`, `left`, or `right`.

+++
