+++
title = "Element-by-element seismic damage diagnosis and prognosis in minimally instrumented woodframe buildings"
date = 2017-01-01T00:00:00  # Schedule page publish date (not talk date).

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Milad Roohi"]

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
time_start = 2018-06-01T13:00:00
time_end = 2018-06-01T15:00:00
all_day = false

# Location of event.
location = "Massachusetts Institute of Technology (MIT), Cambridge, MA, USA"

# Name of event and optional event URL.
event = "Engineering Mechanics Institute Conference 2018 (EMI 2018)"
event_url = "https://example.org"

# Abstract. What's your talk about?
abstract = "I presented an extended model-based state estimator capable of reconstructing nonlinear time-history seismic response of realistic and minimally instrumented building structures. This includes displacements, velocity, acceleration and internal forces in all structural members. The estimator combines sparse velocity measurements and a detailed nonlinear structural model of the building. The methodology is illustrated using data recorded as part of the NEESWood Capstone building shake test conducted at the E-Defense facility in Japan. The nonlinear 3D model of the building was developed using OpenSEES. The model includes every structural wall idealized as a pure shear element capable of resisting horizontal forces in its plane. The force-displacement relationship in each wall is modeled using the SAWS 10-parameter hysteretic model. Various measurement feedback scenarios were tested and the results show that velocity measurements at two floors (3 measurements per floor) are enough to reconstruct the complete nonlinear dynamic response with 95 percent accuracy. Finally, from the estimated dynamic response and structural characteristics of each wall, an element-by-element damage index is computed and remaining useful life (pertaining to seismic effects) is predicted."

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
