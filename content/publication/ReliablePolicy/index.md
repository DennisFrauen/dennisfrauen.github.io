---
title: "Reliable Off-Policy Learning for Dosage Combinations"
authors:
- Jonas Schweisthal
- admin
- Valentyn Melnychuk
- Stefan Feuerriegel
date: "2023-05-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: Preprint
publication_short: Preprint

abstract: Decision-making in personalized medicine such as cancer therapy or critical care must often make choices for dosage combinations, i.e., multiple continuous treatments. Existing work for this task has modeled the effect of multiple treatments independently, while estimating the joint effect has received little attention but comes with non-trivial challenges. In this paper, we propose a novel method for reliable off-policy learning for dosage combinations. Our method proceeds along three steps. (1) We develop a tailored neural network that estimates the individualized dose-response function while accounting for the joint effect of multiple dependent dosages. (2) We estimate the generalized propensity score using conditional normalizing flows in order to detect regions with limited overlap in the shared covariate-treatment space. (3) We present a gradient-based learning algorithm to find the optimal, individualized dosage combinations. Here, we ensure reliable estimation of the policy value by avoiding regions with limited overlap. We finally perform an extensive evaluation of our method to show its effectiveness. To the best of our knowledge, ours is the first work to provide a method for reliable off-policy learning for optimal dosage combinations. 

# Summary. An optional shortened abstract.
summary: We propose a novel method for reliable off-policy learning for dosage combinations under potential overlap violations.

tags:
- Source Themes
featured: false

links:
url_pdf: https://arxiv.org/pdf/2305.19742.pdf
url_code: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 

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
slides: ""
---

