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
height = "500px"

# Slides.
# Duplicate an `[[item]]` block to add more slides.
[[item]]
  title = "Beer In My Vodka :beer:"
  content = ""
  align = "right"  # Choose `center`, `left`, or `right`.

  # Overlay a color or image (optional).
  #   Deactivate an option by commenting out the line, prefixing it with `#`.
  # overlay_color = "#666"  # An HTML color value.
  # Image path relative to your `static/img/` folder.
  overlay_img = "beer-in-my-vodka.png"  
  # Darken the image. Value in range 0-1.
  overlay_filter = 0.3

  # Call to action button (optional).
  #   Activate the button by specifying a URL and button label below.
  #   Deactivate by commenting out parameters, prefixing lines with `#`.
  cta_label = "Official lyrics video"
  cta_url = "https://www.youtube.com/watch?v=p52MkZufIO0"
  cta_icon_pack = "fab"
  cta_icon = "youtube"

[[item]]
  title = "Tunes in progress"
  content = "More and more good songs are coming :microphone:"
  align = "center"

  # overlay_color = "#000000"  # An HTML color value.
  overlay_img = "slider/ouf.jpeg"  # Image path relative to your `static/img/` folder.
  overlay_filter = 0.8  # Darken the image. Value in range 0-1.

  cta_label = "Tune me in!"
  cta_url = "https://soundcloud.com/user-630155630"
  cta_icon_pack = "fab"
  cta_icon = "soundcloud"  

# [[item]]
#  title = "Right"
#  content = "I am right aligned :smile:"
#  align = "right"

#  overlay_color = "#333"  # An HTML color value.
#  overlay_img = ""  # Image path relative to your `static/img/` folder.
#  overlay_filter = 0.5  # Darken the image. Value in range 0-1.
+++
