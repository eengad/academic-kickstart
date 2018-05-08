+++
title = "Active Learning for Community Detection in Stochastic Block Models"
date = 2016-07-10T17:26:45-07:00
draft = false

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["A. Gabbe", "E. En Gad", "S. Avestimehr",  "A. Ortega"]

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
publication = "In *IEEE International Symposium on Information Theory*"
publication_short = "In *ISIT*"

# Abstract and optional shortened version.
abstract = "The stochastic block model (SBM) is an important generative model for random graphs in network science and machine learning, useful for benchmarking community detection (or clustering) algorithms. The symmetric SBM generates a graph with $2n$ nodes which clusters into two equally sized communities. Nodes connect with probability $p$ within a community and $q$ across different communities. We consider the case of $p=a\\ln (n)/n$ and $q=b\\ln (n)/n$. In this case, it was recently shown that recovering the community membership (or label) of every node with high probability (w.h.p.) using only the graph, is possible if and only if the Chernoff-Hellinger (CH) divergence $D(a,b)\\doteq(\\sqrt{a}-\\sqrt{b})^2 \\geq 1$. In this work, we study if, and by how much, community detection below the clustering threshold (i.e. $D(a,b)<1$) is possible by querying the labels of a limited number of chosen nodes (i.e., active learning). Our main result is to show that, under certain conditions, sampling the labels of a vanishingly small fraction of nodes (a number sub-linear in $n$) is sufficient for exact community detection even when $D(a,b)<1$. Furthermore, we provide an efficient learning algorithm which recovers the community memberships of all nodes w.h.p. as long as the number of sampled points meets the sufficient condition. We also show that recovery is not possible if the number of observed labels is less than $n^{1-D(a,b)}$. The validity of our results is demonstrated through numerical experiments."
abstract_short = ""

# Featured image thumbnail (optional)
image_preview = ""

# Is this a selected publication? (true/false)
selected = true

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter the filename (excluding '.md') of your project file in `content/project/`.
#   E.g. `projects = ["deep-learning"]` references `content/project/deep-learning.md`.
projects = []

# Tags (optional).
#   Set `tags = []` for no tags, or use the form `tags = ["A Tag", "Another Tag"]` for one or more tags.
tags = []

# Links (optional).
url_pdf = ""
url_preprint = "https://arxiv.org/abs/1605.02372"
url_code = ""
url_dataset = ""
url_project = ""
url_slides = ""
url_video = ""
url_poster = ""
url_source = ""

# Custom links (optional).
#   Uncomment line below to enable. For multiple links, use the form `[{...}, {...}, {...}]`.
url_custom  = [{name = "IEEE XPlore", url = "http://ieeexplore.ieee.org/document/7541627/"}]

# Does this page contain LaTeX math? (true/false)
math = true

# Does this page require source code highlighting? (true/false)
highlight = true

# Featured image
# Place your image in the `static/img/` folder and reference its filename below, e.g. `image = "example.jpg"`.
[header]
image = ""
caption = ""

+++
