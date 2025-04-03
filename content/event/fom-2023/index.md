---
title: Real-time Recurrent Neural Network-based Fluorescence Lifetime Imaging with SPAD Sensors

event: Focus on Microscopy 2023
event_url: https://cdgdep54fthj76t.focusonmicroscopy.org/

location: Centro de Congressos da Alfândega do Porto
address:
  street: Rua Nova da Alfândega
  city: Porto
  country: Portugal

summary:
abstract: 'Fluorescence lifetime imaging (FLI) has been receiving increased attention in recent years as a powerful imaging technique in biological and medical research. However, existing FLI systems often suffer from a tradeoff between processing speed, accuracy, and robustness. In this paper, we propose a recurrent neural network (RNN) based FLI system that accurately estimates fluorescence lifetime directly from raw timestamps instead of histograms. This process is done on the fly, in real time, as shown in Figure A. We train two variants of the RNN on a synthetic dataset and compare the results to those obtained using the center-of-mass (CMM) and least squares fitting (LSF) methods. The results demonstrate that two RNN variants, gated recurrent unit (GRU) and long short-term memory (LSTM), are comparable to CMM and LSF in terms of accuracy and outperform CMM and LSF by a large margin in the presence of background noise. We also looked at the Cramer-Rao lower bound and detailed analysis showed that the RNN models are close to the theoretical optima. The analysis of experimental data shows that our model, which is purely trained on synthetic datasets, works well on real-world data, as shown in Figure B. We build a FLI microscope setup for evaluation based on Piccolo, a 32x32 SPAD sensor developed in our lab. Four quantized GRU cores, capable of processing 4 million photons per second, are deployed on a Xilinx Kintex-7 FPGA. Powered by the GRU, the FLI setup can retrieve real-time fluorescence lifetime images at up to 10 frames per second (Figure C). The proposed FLI system is promising for many important biomedical applications, ranging from biological imaging of fast-moving cells to fluorescenceassisted diagnosis and surgeries.'

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: '2023-04-04T14:20:00Z'
date_end: '2023-04-04T14:40:00Z'
all_day: false

# Schedule page publish date (NOT talk date).
# publishDate: '2022-12-07T00:00:00Z'

authors: [admin]
tags: [Presentation, FLI, FLIM, RNN, SPAD]

# Is this a featured talk? (true/false)
featured: false

links:
  - icon: twitter
    icon_pack: fab
    name: Follow
    url: https://twitter.com/yangjlin
url_code: ''
url_pdf: ''
url_slides: 'https://cdgdep54fthj76t.focusonmicroscopy.org/2023-program-online/?source=pp&event_id=1791&tab=pdf&a_id=2273'
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

