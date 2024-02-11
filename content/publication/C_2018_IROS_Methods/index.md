---
title: 'Methods for Autonomous Wristband Placement with a Search-and-Rescue Aerial Manipulator'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Jesus M. Gomez-de-Gabriel
  - admin
  - Francisco J. Perez-Maldonado
  - Francisco J. García-Nuñez
  - Emilio J. Fern ́andez-García
  - Alfonso J. García-Cerezo

# Author notes (optional)
author_notes:
  # - 'Equal contribution'
  # - 'Equal contribution'

date: '2018-10-01'
doi: 'https://doi.org/10.1109/IROS.2018.8594202'

# Schedule page publish date (NOT publication's date).
# publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: In IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS) 2018
publication_short: IROS 2018

abstract: A new robotic system for Search And Rescue (SAR) operations based on the automatic wristband placement on the victims’ arm, which may provide identification, beaconing and remote sensor readings for continuous health monitoring. This paper focuses on the development of the automatic target localization and the device placement using an unmanned aerial manipulator. The automatic wrist detection and localization system uses an RGB-D camera and a convolutional neural network based on the region faster method (Faster R-CNN). A lightweight parallel delta manipulator with a large workspace has been built, and a new design of a wristband in the form of a passive detachable gripper, is presented, which under contact, automatically attaches to the human, while disengages from the manipulator. A new trajectory planning method has been used to minimize the torques caused by the external forces during contact, which cause attitude perturbations. Experiments have been done to evaluate the machine learning method for detection and location, and for the assessment of the performance of the trajectory planning method. The results show how the VGG-16 neural network provides a detection accuracy of 67.99%. Moreover, simulation experiments have been done to show that the new trajectories minimize the perturbations to the aerial platform.


# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: [Conferences, Search and Rescue, Robot Design]

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
url_slides: 'presentation.pdf'
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
