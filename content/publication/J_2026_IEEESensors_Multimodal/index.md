---
title: 'Multimodal haptic object recognition: Can kinesthetic inference compensate for the lack of tactile sensing resolution?'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Francisco Pastor
  - Da-hui Lin-Yang
  - Alfonso J. García-Cerezo
  - admin

# Author notes (optional)
author_notes:
  # - 'Equal contribution'
  # - 'Equal contribution'
  # - 'Equal contribution'

date: '2026-04-21'
doi: '10.1109/JSEN.2026.3684076'

# Schedule page publish date (NOT publication's date).
# publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Legend: uncategorized, conference, journal; preprint; book; chapter; thesis; patent
publication_types: ['journal']

# Publication name and optional abbreviated publication name.
publication: In IEEE Sensors Journal
publication_short: In Robotics and Autonomous Systems

abstract: <div align="justify">Haptic perception arises from the integration of cutaneous and kinesthetic cues, yet achieving human‑level tactile performance in robotic systems remains technically demanding and economically costly. This raises a fundamental question. How much does spatial resolution truly matter for robotic touch, and can kinesthetic inference compensate when tactile resolution is limited? To investigate this, we conduct a study on haptic object recognition using an underactuated, sensorized gripper equipped with a high‑resolution tactile array and joint angle sensors. We evaluate a dataset of 36 objects collected under a squeeze-and-release exploratory procedure (EP). Tactile sequences are downsampled to four resolutions (100\%, 75\%, 50\%, and 25\%) using bicubic interpolation, and ConvLSTM-based models are trained to quantify accuracy degradation as spatial detail decreases. We then use two fusion strategies from our previous work: Bayesian inference and neural-based inference, which combine tactile and kinesthetic modalities, and assess whether kinesthetic cues can offset the loss of tactile precision. The results quantify the performance drop as tactile resolution decreases and uncover promising evidence that multimodal fusion can partially recover this lost capability. Interestingly, the two fusion methods exhibit distinct behaviors in terms of robustness and consistency. As discussed comprehensively in the manuscript, these findings suggest that, under the right conditions, reliable object recognition may not depend solely on maintaining high tactile resolution, opening new possibilities for designing more scalable and cost‑efficient haptic perception systems.</div>


# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: [Journal, Haptic Perception]

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

# To add the pdf save the file named `FOLDER_NAME.pdf` to your page's folder.
url_pdf: ''
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: ''
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
# projects:
  # - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---

<!-- {{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/). -->
