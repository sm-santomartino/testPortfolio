---
title: Can AI Handle the Stress? A Robustness Evaluation of a State-of-the-Art Deep Learning Bone Age Algorithm.
event: Radiological Society of North America 108th Scientific Assembly and Annual Meeting
event_url: https://www.rsna.org/annual-meeting/future-and-past-meetings
location: Chicago, IL
summary: Podium Presentation
abstract: "**Purpose:** Although deep learning (DL) models for bone age prediction have been shown to perform similarly to radiologists, their robustness to real-world image variation has not been rigorously evaluated. We evaluated the robustness of a state-of-the-art bone age DL model to real-world variations in images by applying computational 'stress tests.' **Methods and Materials:** We evaluated the winning DL model of the 2017 RSNA Pediatric Bone Age Challenge (concordance of 0.991 with radiologist ground-truth) using an internal test set of 1425 images from the RSNA Challenge and an external dataset of 1202 images from the Digital Hand Atlas (DHA). We applied simple transformations to each test image to simulate real-world variations: 1) rotations, 2) flips, 3) brightness adjustments, 4) contrast adjustments, 5) inverted pixels, 6) addition of a standard radiological laterality marker, and 7) resolution changes from baseline of 1024x1024. We performed computational “stress tests” by comparing mean absolute differences (MAD) of the model’s predictions on baseline (untransformed) vs. transformed images with t-tests, as well as proportions of clinically significant errors (those that would change the clinical diagnosis) in the external dataset using Chi-Squared tests (the internal dataset did not report chronological age, precluding evaluation of clinically significant errors). **Results:** There was no significant difference in MAD of the model on baseline internal and external test images, indicating good generalizability. On computational stress testing, the model had significantly higher MAD and proportions of clinically significant errors in transformed images compared to baseline images for all image transformation groups (p &lt; 0.05, all), except for addition of laterality markers. For example, for 180 degree rotations, predicted bone age was significantly lower (97.8 months vs. 135.2 months, p &lt; 0.0001) and MAD was significantly higher (45.2 months vs. 6.9 months, p &lt; 0.0001) with 30% more clinically significant errors (p &lt; 0.0001) compared to baseline images. **Conclusions:** Although a state-of-the-art bone age DL model generalized well to external data, it had inconsistent predictions on images that had undergone simple transformations reflective of clinical variations in radiograph processing. Our results indicate that DL models may not perform as expected in the real world and that they should be thoroughly stress tested prior to deployment in order to determine if they are 'clinic ready.' **Clinical Relevance/Application:** A state-of-the-art bone age deep learning algorithm had clinically significant errors when presented with clinically-encountered imaging variations, suggesting lack of clinic-readiness for real-world deployment."

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: "2022-11-27T13:00:00Z"
date_end: ""
all_day: true

# Schedule page publish date (NOT talk date).
publishDate: ""

authors: []
tags: []

# Is this a featured talk? (true/false)
featured: false

image:
  caption: 
  focal_point: Right

links:
#- icon: twitter
#  icon_pack: fab
#  name: Follow
#  url: https://twitter.com/georgecushen
url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""

# Markdown Slides (optional).
#   Associate this talk with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: 

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects:
# - internal-project

# Enable math on this page?
math: true
---
