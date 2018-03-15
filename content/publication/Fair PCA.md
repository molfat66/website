+++
title = "FPCA"
date = 2018-03-15T01:25:54-07:00
draft = false

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Matt Olfat", "Anil Aswani"]

# Publication type.
# Legend:
# 0 = Uncategorized
# 1 = Conference paper
# 2 = Journal article
# 3 = Manuscript
# 4 = Report
# 5 = Book
# 6 = Book section
publication_types = ["1"]

# Publication name and optional abbreviated version.
publication = "Convex formulations for fair principal component analysis"
publication_short = "Fair PCA"

# Abstract and optional shortened version.
abstract = "Though there is a growing body of literature on fairness for supervised learning, the problem of incorporating fairness into unsupervised learning has been less well-studied. This paper studies fairness in the context of principal component analysis (PCA). We first present a definition of fairnessfordimensionalityreduction,andourdefinition can be interpreted as saying that a reduction is fair if information about a protected class (e.g., race or gender) cannot be inferred from the dimensionality-reduced data points. Next, we develop convex optimization formulations that can improve the fairness (with respect to our definition) of PCA and kernel PCA. These formulations are semidefinite programs (SDPs), and we demonstrate the effectiveness of our formulations using several datasets. We conclude by showing how our approach can be used to perform a fair (with respect to age) clustering of health data that may be used to set health insurance rates."
abstract_short = ""

# Featured image thumbnail (optional)
image_preview = "fpca.jpg"

# Is this a selected publication? (true/false)
selected = true

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter the filename (excluding '.md') of your project file in `content/project/`.
#   E.g. `projects = ["deep-learning"]` references `content/project/deep-learning.md`.
projects = ["Fairness in machine learning"]

# Tags (optional).
#   Set `tags = []` for no tags, or use the form `tags = ["A Tag", "Another Tag"]` for one or more tags.
tags = ["Fairness", "PCA", "Unsupervised Learning"]

# Links (optional).
url_pdf = ""
url_preprint = "https://arxiv.org/pdf/1802.03765.pdf"
url_code = "https://github.com/molfat66/FairML"
url_dataset = ""
url_project = ""
url_slides = ""
url_video = ""
url_poster = ""
url_source = ""

# Custom links (optional).
#   Uncomment line below to enable. For multiple links, use the form `[{...}, {...}, {...}]`.
# url_custom = [{name = "Custom Link", url = "http://example.org"}]

# Does this page contain LaTeX math? (true/false)
math = false

# Does this page require source code highlighting? (true/false)
highlight = true

# Featured image
# Place your image in the `static/img/` folder and reference its filename below, e.g. `image = "example.jpg"`.
[header]
image = "fpca.jpg"
caption = ""

+++
