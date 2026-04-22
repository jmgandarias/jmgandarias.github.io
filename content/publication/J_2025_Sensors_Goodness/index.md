---
title: 'Goodness of Fit in the Marginal Modeling of Round-Trip Times for Networked Robot Sensor Transmissions'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Juan-Antonio Fernández-Madrigal
  - Vicente Arévalo-Espejo
  - Ana Cruz-Martín
  - Cipriano Galindo-Andrades
  - Adrián Bañuls-Arias
  - admin

# Author notes (optional)
author_notes:
  # - 'Equal contribution'
  # - 'Equal contribution'
  # - 'Equal contribution'

date: '2025-09-02'
doi: '10.3390/s25175413'

# Schedule page publish date (NOT publication's date).
# publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Legend: uncategorized, conference, journal; preprint; book; chapter; thesis; patent
publication_types: ['journal']

# Publication name and optional abbreviated publication name.
publication: In MDPI Sensors
publication_short: In MDPI Sensors

abstract: <div align="justify">When complex computations cannot be performed on board a mobile robot, sensory data must be transmitted to a remote station to be processed, and the resulting actions must be sent back to the robot to execute, forming a repeating cycle. This involves stochastic round-trip times in the case of non-deterministic network communications and/or non-hard real-time software. Since robots need to react within strict time constraints, modeling these round-trip times becomes essential for many tasks. Modern approaches for modeling sequences of data are mostly based on time-series forecasting techniques, which impose a computational cost that may be prohibitive for real-time operation, do not consider all the delay sources existing in the sw/hw system, or do not work fully online, i.e., within the time of the current round-trip. Marginal probabilistic models, on the other hand, often have a lower cost, since they discard temporal dependencies between successive measurements of round-trip times, a suitable approximation when regime changes are properly handled given the typically stationary nature of these round-trip times. In this paper we focus on the hypothesis tests needed for marginal modeling of the round-trip times in remotely operated robotic systems with the presence of abrupt changes in regimes. We analyze in depth three common models, namely Log-logistic, Log-normal, and Exponential, and propose some modifications of parameter estimators for them and new thresholds for well-known goodness-of-fit tests, which are aimed at the particularities of our setting. We then evaluate our proposal on a dataset gathered from a variety of networked robot scenarios, both real and simulated; through >2100 h of high-performance computer processing, we assess the statistical robustness and practical suitability of these methods for these kinds of robotic applications.</div>


# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: [Journal, Round-trip times modeling, networked robots]

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
