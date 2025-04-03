---
title: Real-time neural network-based fluorescence lifetime imaging with SPAD sensors 

event: BMPN 2022
event_url: https://bmpn2022.ch/

location: EPFL
address:
  street: Rte Cantonale
  city: Lausanne
  region: Vaud
  postcode: '1015'
  country: Switzerland

summary:
abstract: 'Fluorescence lifetime imaging (FLI) is a powerful imaging technique in biological and medical research, which is receiving increased attention for clinical applications in recent years. However, existing FLI systems often suffer from the tradeoff among processing speed, accuracy, and robustness. Herein, we propose a recurrent neural network (RNN)-based FLI system that accurately estimates the fluorescence lifetime, from the raw timestamps instead of histograms, on the fly. We train variants of RNNs on a synthetic dataset and compare them to center-of-mass method (CMM) and least squares fitting (LSF). The results demonstrate that two RNN variants, gated recurrent unit (GRU) and long short-term memory (LSTM), are comparable to CMM and LSF in terms of accuracy and outperform CMM and LSF by a large margin in the presence of background noise. Besides, the Cramer-Rao lower bound analysis shows that the RNN models are close to the theoretical optima. We build a FLI microscope setup for evaluation, utilizing Piccolo, a 32x32 SPAD sensor developed by our lab. Four quantized GRU cores, capable of processing 4 million photons per second, are deployed on a Xilinx Kintex-7 FPGA. Powered by the GRU, the FLI setup can retrieve real-time fluorescence lifetime images up to 10 frames per second. With these advantages, the proposed FLI system is promising for many important biomedical applications ranging from biological imaging of fast-moving cells to fluorescence-assisted diagnosis and surgeries.'

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: '2022-12-06T10:10:00Z'
date_end: '2022-12-06T10:25:00Z'
all_day: false

# Schedule page publish date (NOT talk date).
publishDate: '2022-12-07T00:00:00Z'

authors: [admin]
tags: [Presentation, FLI, FLIM, RNN, SPAD]

# Is this a featured talk? (true/false)
featured: false

image:
  caption: ''
  focal_point: ''

links:
  - icon: twitter
    icon_pack: fab
    name: Follow
    url: https://twitter.com/yangjlin
url_code: ''
url_pdf: ''
url_slides: 'https://docs.google.com/presentation/d/1Prub65G18_mOEukl5QIm_p1DFvtjH_AX/edit?usp=sharing&ouid=105659257542408476609&rtpof=true&sd=true'
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

<!-- {{% callout note %}}
Click on the **Slides** button above to view the built-in slides feature.
{{% /callout %}}

Slides can be added in a few ways:

- **Create** slides using Wowchemy's [_Slides_](https://wowchemy.com/docs/managing-content/#create-slides) feature and link using `slides` parameter in the front matter of the talk file
- **Upload** an existing slide deck to `static/` and link using `url_slides` parameter in the front matter of the talk file
- **Embed** your slides (e.g. Google Slides) or presentation video on this page using [shortcodes](https://wowchemy.com/docs/writing-markdown-latex/).

Further event details, including [page elements](https://wowchemy.com/docs/writing-markdown-latex/) such as image galleries, can be added to the body of this page. -->

I am honored to receive the **Award for the Best Talk of a Young Researcher** at BMPN 2022.
