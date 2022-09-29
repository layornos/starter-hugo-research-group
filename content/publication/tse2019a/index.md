---
title: 'Scalability testing automation using multivariate characterization and detection of software performance antipatterns'
authors:
  - Alberto Avritzer
  - Ricardo Britto
  - Catia Trubiani
  - Matteo Camilli
  - Andrea Camilli
  - Barbara Russo
  - André van Hoorn
  - robert
  - Martina Rapp
  - Jörg Henß
  - Ram Kishan Chalawadi
date: '2022-09-01T00:00:00Z'
doi: 'doi:10.1016/j.jss.2022.111446'

# Schedule page publish date (NOT publication's date).
publishDate: '2022-09-01T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['2']

# Publication name and optional abbreviated publication name.
publication: 'Journal of Systems and Software'
publication_short: 'SoSym'

abstract: Software Performance Antipatterns (SPAs) research has focused on algorithms for their characterization, detection, and solution. Existing algorithms are based on the analysis of runtime behavior to detect trends on several monitored variables, such as system response time and CPU utilization. However, the lack of computationally efficient methods currently limits their integration into modern agile practices to detect SPAs in large scale systems. In this paper, we extended our previously proposed approach for the automated SPA characterization and detec- tion designed to support continuous integration/delivery/deployment (CI/CDD) pipelines, with the goal of addressing the lack of computationally efficient algorithms. We introduce a machine learning-based approach to improve the detection of SPA and interpretation of approach’s results. The approach is complemented with a simulation-based methodology to analyze different architectural alternatives and measure the precision and recall of our approach. Our approach includes SPA statistical characterization using a multivariate analysis of load testing experimental results to identify the services that have the largest impact on system scalability. To show the effectiveness of our approach, we have applied it to a large complex telecom system at Ericsson. We have built a simulation model of the Ericsson system and we have evaluated the introduced methodology by using simulation-based SPA injection. For this system, we are able to automatically identify the top five services that represent scalability choke points. We applied two machine learning algorithms for the automated detection of SPA. We contributed to the state-of-the-art by introducing a novel approach to support computationally efficient SPA characterization and detection that has been applied to a large complex system using performance testing data. We have compared the computational efficiency of the proposed approach with state-of-the-art heuristics. We have found that the approach introduced in this paper grows linearly, which is a significant improvement over existing techniques.

# Summary. An optional shortened abstract.
summary: In this paper, we have extended our previously proposed approach for the characterization and the detection of SPAs that was designed to be integrated into CI/CDD pipelines, and its implementation is computationally efficient.

tags:
  - Source Themes
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: 'https://www.sciencedirect.com/science/article/abs/pii/S016412122200142X?via%3Dihub'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# image:
  #caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/jdD8gXaTZsc)'
  #focal_point: ''
  #preview_only: false

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
slides:
---

