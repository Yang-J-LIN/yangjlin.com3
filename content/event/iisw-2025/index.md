---
title: 'Transporter: A 128×4 SPAD Imager with On-chip Encoder for Spiking Neural Network-based Processing'

event: International Image Sensor Workshop (IISW) 2025
event_url: https://imagesensors.org/2025-international-image-sensor-workshop/

location: Awaji Yumebutai Int. Conf. Center
address:
  street: Yumebutai 1
  city: Awaji
  region: Hyogo
  postcode: '656-2306'
  country: Japan

summary:
abstract: 'Single-photon avalanche diodes (SPADs) are widely used today in time-resolved imaging applications, however traditional architectures rely on time-to-digital converters (TDCs) and histogram-based processing, leading to significant data transfer and processing challenges. Previous work based on recurrent neural networks has realized histogram-free processing. To further address these limitations, we propose a novel paradigm that eliminates TDCs by integrating in-sensor spike encoders. This approach enables preprocessing of photon arrival events in the sensor while significantly compressing data, reducing complexity, and maintaining real-time edge processing capabilities. A dedicated spike encoder folds multiple laser repetition periods, transforming phase-based spike trains into density-based spike trains optimized for spiking neural network processing and training via backpropagation through time. As a proof of concept, we introduce \textit{Transporter}, a 128$\times$4 SPAD sensor with a per-pixel D flip-flop ring-based spike encoder, designed for intelligent active time-resolved imaging. This work demonstrates a path toward more efficient, neuromorphic SPAD imaging systems with reduced data overhead and enhanced real-time processing.'

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: '2025-06-02T16:30:00Z'
date_end: '2025-06-02T19:30:00Z'
all_day: false

# Schedule page publish date (NOT talk date).
publishDate: '2025-04-04T00:00:00Z'

authors: [admin]
tags: [Poster, FLI, FLIM, SNN, SPAD, Edge AI]

# Is this a featured talk? (true/false)
featured: false

links:
  - icon: twitter
    icon_pack: fab
    name: Follow
    url: https://twitter.com/yangjlin
url_code: ''
url_pdf: ''
url_slides: ''
url_video: ''

# Markdown Slides (optional).
#   Associate this talk with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
# slides: example

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
# projects:
#   - example
---

I will present in the flash presentation and poster session. Feel free to discuss with me during the poster session!

<!-- {{% callout note %}}
Click on the **Slides** button above to view the built-in slides feature.
{{% /callout %}}

Slides can be added in a few ways:

- **Create** slides using Wowchemy's [_Slides_](https://wowchemy.com/docs/managing-content/#create-slides) feature and link using `slides` parameter in the front matter of the talk file
- **Upload** an existing slide deck to `static/` and link using `url_slides` parameter in the front matter of the talk file
- **Embed** your slides (e.g. Google Slides) or presentation video on this page using [shortcodes](https://wowchemy.com/docs/writing-markdown-latex/).

Further event details, including [page elements](https://wowchemy.com/docs/writing-markdown-latex/) such as image galleries, can be added to the body of this page. -->

