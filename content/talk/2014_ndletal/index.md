---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Speeding up active mesh segmentation by local termination of nodes"
event: "Medical Image Understanding and Analysis"
event_url: "https://www.city.ac.uk/events/conferences/medical-image-understanding-and-analysis-2014"
location: "London UK"
summary:
abstract: "This article outlines a procedure for speeding up segmentation of images using active mesh systems.  Active meshes and other deformable models are very popular in image segmentation due to their ability to capture weak or missing boundary information; however, where strong edges exist, computations are still done after mesh nodes have settled on the boundary.  This can lead to extra computational time whilst the system continues to deform completed regions of the mesh. We propose a local termination procedure, reducing these unnecessary computations and speeding up segmentation time with minimal loss of quality."

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: 2014-07-10T12:30:00+01:00
date_end: 2014-07-10T14:00:00+01:00
all_day: false

authors: ["chas", "Martin Dixon", "[P. Philippe Laissue](https://www.essex.ac.uk/people/laiss31109/philippe-laissue)", "[Boguslaw Obara](https://community.dur.ac.uk/boguslaw.obara/)"]
tags: []

# Is this a featured talk? (true/false)
featured: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
  preview_only: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

# Optional filename of your slides within your talk's folder or a URL.
url_slides:
url_code:
url_pdf:
url_video:
url_poster: "https://doi.org/10.6084/m9.figshare.8490041"
url_dataset:

# Markdown Slides (optional).
#   Associate this talk with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: ["nuclei-detection"]
---
