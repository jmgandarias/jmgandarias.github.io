---
title: 'Bayesian and Neural Inference on LSTM-based Object Recognition from Tactile and Kinesthetic Information'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Francisco Pastor
  - Jorge García-González
  - admin 
  - Daniel Medina
  - Pau Closas
  - Alfonso J. García-Cerezo
  - Jesús M. Gómez-de-Gabriel

# Author notes (optional)
author_notes:
  # - 'Equal contribution'
  # - 'Equal contribution'

date: '2020-11-16'
doi: '10.1109/LRA.2020.3038377'

# Schedule page publish date (NOT publication's date).
# publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Legend: uncategorized, conference, journal; preprint; book; chapter; thesis; patent
publication_types: ['journal']

# Publication name and optional abbreviated publication name.
publication: In IEEE Robotics and Automation Letters
publication_short: In IEEE RAL

abstract: <div align="justify">Recent advances in the field of intelligent robotic manipulation pursue providing robotic hands with touch sensitivity. Haptic perception encompasses the sensing modalities encountered in the sense of touch (e.g., tactile and kinesthetic sensations). This letter focuses on multimodal object recognition and proposes analytical and data-driven methodologies to fuse tactile- and kinesthetic-based classification results. The procedure is as follows. A three-finger actuated gripper with an integrated high-resolution tactile sensor performs squeeze-and-release Exploratory Procedures (EPs). The tactile images and kinesthetic information acquired using angular sensors on the finger joints constitute the time-series datasets of interest. Each temporal dataset is fed to a Long Short-term Memory (LSTM) Neural Network, which is trained to classify in-hand objects. The LSTMs provide an estimation of the posterior probability of each object given the corresponding measurements, which after fusion allows to estimate the object through Bayesian and Neural inference approaches. An experiment with 36-classes is carried out to evaluate and compare the performance of the fused, tactile, and kinesthetic perception systems. The results show that the Bayesian-based classifiers improves capabilities for object recognition and outperforms the Neural-based approach.</div>


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
url_video: 'video.mp4'

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
