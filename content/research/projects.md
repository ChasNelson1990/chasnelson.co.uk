+++
# A Projects section created with the Portfolio widget.
widget = "portfolio"  # See https://sourcethemes.com/academic/docs/page-builder/
headless = true  # This file represents a page section.
active = true  # Activate this widget? true/false
weight = 20  # Order that this section will appear.

title = ""
subtitle = ""

[content]
  # Page type to display. E.g. project.
  page_type = "project"

  # Filter toolbar (optional).
  # Add or remove as many filters (`[[content.filter_button]]` instances) as you like.
  # To show all items, set `tag` to "*".
  # To filter by a specific tag, set `tag` to an existing tag name.
  # To remove toolbar, delete/comment all instances of `[[content.filter_button]]` below.

  # Default filter index (e.g. 0 corresponds to the first `[[filter_button]]` instance below).
  filter_default = 0

  [[content.filter_button]]
    name = "All"
    tag = "*"

  [[content.filter_button]]
    name = "Current"
    tag = "current"

  [[content.filter_button]]
    name = "Smart Microscopy"
    tag = "microscopy"

  [[content.filter_button]]
    name = "Bioimage Analysis"
    tag = "analysis"

  [[content.filter_button]]
    name = "Data Science"
    tag = "data"

  [[content.filter_button]]
    name = "Vision"
    tag = "vision"

  [[content.filter_button]]
    name = "Biology"
    tag = "biology"

  [[content.filter_button]]
    name = "Health"
    tag = "health"

[design]
  # Choose how many columns the section has. Valid values: 1 or 2.
  columns = "1"

  # Toggle between the various page layout types.
  #   1 = List
  #   3 = Card
  #   5 = Showcase
  view = 3

  # For Showcase view, flip alternate rows?
  flip_alt_rows = true
+++

## Projects