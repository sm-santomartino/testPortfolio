---
title: "Performance and usability of code-free deep learning for chest radiograph classification, object detection, and segmentation."
authors:
- admin
- Nima Hafezi-Nejad
- Vishwa S. Parekh
- Paul H. Yi
date: "2023-02-15T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: ""

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "*Radiology: Aritfical Intelligence*"
publication_short: ""

abstract: "**Purpose:** To evaluate the performance and usability of code-free deep learning (CFDL) platforms in creating DL models for disease classification, object detection, and segmentation on chest radiographs. **Materials and Methods:** Six CFDL platforms were evaluated in this retrospective study (September 2021). Single- and multilabel classifiers were trained for thoracic pathologic conditions using Guangzhou pediatric and NIH-CXR14 (ie, National Institutes of Health ChestX-ray14) datasets, and external testing was performed using subsets of NIH-CXR14 and Stanford CheXpert datasets, respectively. Pneumonia detection and pneumothorax segmentation models were trained using the Radiological Society of North America (RSNA) Pneumonia and Society for Imaging Informatics in Medicine (SIIM) Pneumothorax datasets, respectively. Model performance was evaluated using F1 scores. Usability was evaluated based on feasibility of image uploading and model training, ease of use, and cost. **Results:** NIH-CXR14 and CheXpert datasets contained 112 120 (mean age, 47 years ± 17 [SD]; 63 340 male patients) and 151 522 images (mean age, 61 years ± 18; 88 931 male patients), respectively. The other datasets did not report demographics (Guangzhou, 5826 images; RSNA, 26 683 images; SIIM, 15 301 images). Six platforms offered single-label classifiers, four multilabel classifiers, five object detection models, and one segmentation model. Guangzhou pneumonia classifiers demonstrated good internal (F1, 0.93–0.99) and poor external (F1, 0.39–0.44) performance. Multilabel NIH-CXR14 classifiers showed poor internal and external performance (F1, 0.00–0.36 and 0.00–0.76, respectively). NIH-CXR14 single-label classifiers performed poorly (F1, 0.00, all). The single successfully trained pneumonia detection model had an F1 score of 0.48. No segmentation model was successfully trained. Platform usability was limited, with all requiring some type of coded solution. **Conclusion:** CFDL platforms demonstrated limited performance and usability for chest radiograph analysis."

# Summary. An optional shortened abstract.
summary: "**Purpose:** To evaluate the performance and usability of code-free deep learning (CFDL) platforms in creating DL models for disease classification, object detection, and segmentation on chest radiographs."

tags:
- Artificial Intelligence
- Automated Machine Learning
- Chest Radiographs
- Deep Learning
- Code-Free Deep Learning
- Pneumonia
- Pneumothorax
- Radiology
featured: false

# links:
# - name: ""
#   url: ""
# url_pdf: http://arxiv.org/pdf/1512.04133v1
# url_code: ''
# url_dataset: ''
# url_poster: ''
# url_project: ''
# url_slides: ''
# url_source: ''
# url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---
