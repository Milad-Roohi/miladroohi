+++
title = "Element-by-element seismic damage diagnosis and prognosis in minimally instrumented woodframe buildings"
date = 2017-01-01T00:00:00  # Schedule page publish date (not talk date).

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Milad Roohi"]

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
time_start = 2018-04-01T13:00:00
time_end = 2018-06-01T15:00:00
all_day = false

# Location of event.
location = "Department of Civil and Environmental Engineering, Colorado State University, Fort Collins, Colorado, USA"

# Name of event and optional event URL.
event = "NIST Center of Excellence for Risk-Based Community Resilience Planning"
event_url = "https://example.org"

# Abstract. What's your talk about?
abstract = "This talk presents on-going work on the use of minimal instrumentation to assess the structural integrity of buildings immediately after an earthquake. The proposed methodology combines a nonlinear model of the structure with sparse response measurements, typically in the form of accelerations, to reconstruct the time history response at all stories and in all elements of the structure. The estimator also provides an estimate of uncertainty for all quantities of interest in the form of estimation variance. Using the estimated response, a Park and Ang-type damage index can be reconatructed for every structural  element in the building (with their corresponding uncertainty). The damage index is used to assess the current condition of the structure and its remaining capacity to withstand aftershocks, future earthquakes or any other dynamic loading condition. The methodology is illustrated using data from the 2009 NEESWood Capstone tests. For this implementation, a three-dimensional non-linear shear wall model was developed. Each wall was modeled as an in-plane lateral-force resisting element with a hysteresis characterized by a 10-parameter SAWS model. The methodology was implemented using acceleration measurements from two stories to estimate damage indices for every wall in every story. We envision that in practice the proposed methodology can help reduce post-earthquake inspection/recovery time of critical buildings and increase the seismic resiliency of urban centers."

# Summary. An optional shortened abstract.
summary = ""

# Is this a featured talk? (true/false)
featured = false

# Tags (optional).
#   Set `tags = []` for no tags, or use the form `tags = ["A Tag", "Another Tag"]` for one or more tags.
tags = []

# Markdown Slides (optional).
#   Associate this talk with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references 
#   `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides = "example-slides"

# Optional filename of your slides within your talk folder or a URL.
url_slides = ""

# Projects (optional).
#   Associate this talk with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["deep-learning"]` references 
#   `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects = ["internal-project"]

# Links (optional).
url_pdf = ""
url_video = ""
url_code = ""

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
[image]
  # Caption (optional)
  caption = "Image credit: [**Unsplash**](https://unsplash.com/photos/bzdhc5b3Bxs)"

  # Focal point (optional)
  # Options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
  focal_point = "Right"
+++

{{% alert note %}}
Click on the **Slides** button above to view the built-in slides feature.
{{% /alert %}}

Slides can be added in a few ways:

- **Create** slides using Academic's *Slides* feature and link using `url_slides` parameter in the front matter of the talk file
- **Upload** an existing slide deck to `static/` and link using `url_slides` parameter in the front matter of the talk file
- **Embed** your slides (e.g. Google Slides) or presentation video on this page using [shortcodes](https://sourcethemes.com/academic/docs/writing-markdown-latex/).

Further talk details can easily be added to this page using *Markdown* and $\rm \LaTeX$ math code.
