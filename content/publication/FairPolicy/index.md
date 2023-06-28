---
title: "Fair Off-Policy Learning from Observational Data"
authors:
- admin
- Valentyn Melnychuk
- Stefan Feuerriegel
date: "2023-04-01T00:00:00Z"
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

abstract: Businesses and organizations must ensure that their algorithmic decision-making is fair in order to meet legislative, ethical, and societal demands. For example, decision-making in automated hiring must not discriminate with respect to gender or race. To achieve this, prior research has contributed approaches that ensure algorithmic fairness in machine learning predictions, while comparatively little effort has focused on algorithmic fairness in decision models, specifically off-policy learning. In this paper, we propose a novel framework for fair off-policy learning. We learn decision rules from observational data under different notions of fairness, where we explicitly assume that observational data were collected under a different -- potentially biased -- behavioral policy. For this, we first formalize different fairness notions for off-policy learning. We then propose a machine learning approach to learn optimal policies under these fairness notions. Specifically, we reformulate the fairness notions into unconstrained learning objectives that can be estimated from finite samples. Here, we leverage machine learning to minimize the objective constrained on a fair representation of the data, so that the resulting policies satisfy our fairness notions. We further provide theoretical guarantees in form of generalization bounds for the finite-sample version of our framework. We demonstrate the effectiveness of our framework through extensive numerical experiments using both simulated and real-world data. As a result, our work enables algorithmic decision-making in a wide array of practical applications where fairness must ensured. 

# Summary. An optional shortened abstract.
summary: We propose a machine learning approach for learning fair optimal policies from observational data.

tags:
- Source Themes
featured: false

links:
url_pdf: https://arxiv.org/abs/2303.08516.pdf
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

