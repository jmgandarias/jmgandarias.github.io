---
title: 'Using 3D Convolutional Neural Networks for Tactile Object Recognition with Robotic Palpation'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Francisco Pastor
  - admin 
  - Alfonso J. García-Cerezo
  - Jesús M. Gómez-de-Gabriel

# Author notes (optional)
author_notes:
  # - 'Equal contribution'
  # - 'Equal contribution'

date: '2019-12-05'
doi: '10.3390/s19245356'

# Schedule page publish date (NOT publication's date).
# publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Legend: uncategorized, conference, journal; preprint; book; chapter; thesis; patent
publication_types: ['journal']

# Publication name and optional abbreviated publication name.
publication: In MDPI Sensors
publication_short: In MDPI Sensors

abstract: <div align="justify">In this paper, a novel method of active tactile perception based on 3D neural networks and a high-resolution tactile sensor installed on a robot gripper is presented. A haptic exploratory procedure based on robotic palpation is performed to get pressure images at different grasping forces that provide information not only about the external shape of the object, but also about its internal features. The gripper consists of two underactuated fingers with a tactile sensor array in the thumb. A new representation of tactile information as 3D tactile tensors is described. During a squeeze-and-release process, the pressure images read from the tactile sensor are concatenated forming a tensor that contains information about the variation of pressure matrices along with the grasping forces. These tensors are used to feed a 3D Convolutional Neural Network (3D CNN) called 3D TactNet, which is able to classify the grasped object through active interaction. Results show that 3D CNN performs better, and provide better recognition rates with a lower number of training data.</div>


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
