---
title: "Estimating individual treatment effects under unobserved confounding using binary instruments"
authors:
- admin
- Stefan Feuerriegel
date: "2023-01-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: Accepted at *ICLR 2023*
publication_short: Accepted at *ICLR 2023*

abstract: Estimating conditional average treatment effects (CATEs) from observational data is relevant in many fields such as personalized medicine. However, in practice, the treatment assignment is usually confounded by unobserved variables and thus introduces bias. A remedy to remove the bias is the use of instrumental variables (IVs). Such settings are widespread in medicine (e.g., trials where the treatment assignment is used as binary IV). In this paper, we propose a novel, multiply robust machine learning framework, called MRIV, for estimating CATEs using binary IVs and thus yield an unbiased CATE estimator. Different from previous work for binary IVs, our framework estimates the CATE directly via a pseudo outcome regression. (1)~We provide a theoretical analysis where we show that our framework yields multiple robust convergence rates, that is, our CATE estimator achieves fast convergence even if several nuisance estimators converge slowly. (2)~We further show that our framework asymptotically outperforms state-of-the-art plug-in IV methods for CATE estimation, in the sense that it achieves a faster rate of convergence if the CATE is smoother than the individual outcome surfaces. (3)~We build upon our theoretical results and propose a tailored deep neural network architecture called MRIV-Net for CATE estimation using binary IVs. Across various computational experiments, we demonstrate empirically that our MRIV-Net achieves state-of-the-art performance. To the best of our knowledge, our MRIV is the first multiply robust machine learning framework tailored to estimating CATEs in the binary IV setting.

# Summary. An optional shortened abstract.
summary: We propose a multiple robust robust machine learning framework for estimating individual treatment effects under unobserved confounding when binary instruments are available.

tags:
- Source Themes
featured: true

links:
url_pdf: https://arxiv.org/pdf/2208.08544.pdf
url_code: 'https://github.com/DennisFrauen/MRIV-Net'

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

