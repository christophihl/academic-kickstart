+++
# Slider widget.
widget = "slider"  # See https://sourcethemes.com/academic/docs/page-builder/
headless = true  # This file represents a page section.
active = true  # Activate this widget? true/false
weight = 10  # Order that this section will appear.

# Slide interval.
# Use `false` to disable animation or enter a time in ms, e.g. `5000` (5s).
interval = 5000

# Slide height (optional).
# E.g. `500px` for 500 pixels or `calc(100vh - 70px)` for full screen.
height = ""

# Slides.
# Duplicate an `[[item]]` block to add more slides.
[[item]]
  title = "Team"
  content = "Unsere Kompetenzen und Ansprechpartner."
  align = "left"  # Choose `center`, `left`, or `right`.

  # Overlay a color or image (optional).
  #   Deactivate an option by commenting out the line, prefixing it with `#`.
  # overlay_color = "#666"  # An HTML color value.
  overlay_img = "computer_blue.jpg"  # Image path relative to your `static/img/` folder.
  overlay_filter = 0.1  # Darken the image. Value in range 0-1.

  # Call to action button (optional).
  #   Activate the button by specifying a URL and button label below.
  #   Deactivate by commenting out parameters, prefixing lines with `#`.
  cta_label = "Treffen Sie unser Team."
  cta_url = "/team/"
  cta_icon_pack = "fas"
  cta_icon = "users"

[[item]]
  title = "Forschung"
  content = "Unsere Arbeit in Projekten und Publikationen."
  align = "left"

  # overlay_color = "#555"  # An HTML color value.
  overlay_img = "waves_blue.jpg"  # Image path relative to your `static/img/` folder.
  overlay_filter = 0.1  # Darken the image. Value in range 0-1.

  cta_label = "Unsere Forschung entdecken."
  cta_url = "/research/"
  cta_icon_pack = "fas"
  cta_icon = "search"

[[item]]
  title = "MLE-Days"
  content = "Konferenz zu ML-Forschung und Engineering-Anwendung."
  align = "left"

  # overlay_color = "#333"  # An HTML color value.
  overlay_img = "platinen_blue.jpg"  # Image path relative to your `static/img/` folder.
  overlay_filter = 0.1  # Darken the image. Value in range 0-1.

  cta_label = "Save the date."
  cta_url = "/conference/"
  cta_icon_pack = "fas"
  cta_icon = "users"

[[item]]
  title = "Praxistransfer"
  content = "Unsere Angebote von Workshops bis zu F&E-Projekten."
  align = "left"

  # overlay_color = "#333"  # An HTML color value.
  overlay_img = "robotic_blue.jpg"  # Image path relative to your `static/img/` folder.
  overlay_filter = 0.1 # Darken the image. Value in range 0-1.

  cta_label = "Arbeiten Sie mit uns."
  cta_url = "/practice/"
  cta_icon_pack = "fas"
  cta_icon = "cogs"


+++
