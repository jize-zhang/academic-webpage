+++
title = "Multi-objective optimization for design under uncertainty problems through surrogate modeling in augmented input space"

# Date first published.
date = "2018-09-18"

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Jize Zhang", "Alexandros Taflanidis"]

# Publication type.
# Legend:
# 0 = Uncategorized
# 1 = Conference proceedings
# 2 = Journal
# 3 = Work in progress
# 4 = Technical report
# 5 = Book
# 6 = Book chapter
publication_types = ["2"]

# Publication name and optional abbreviated version.
publication = "Structural and Multidisciplinary Optimization"
publication_short = "SMO"

# Abstract and optional shortened version.
abstract = "Multi-objective design under uncertainty problems that adopt probabilistic quantities as performance objectives and consider their estimation through stochastic simulation are examined in this paper, focusing on development of a surrogate modeling framework to reduce computational burden for the numerical optimization. The surrogate model is formulated to approximate the system response with respect to both the design variables and the uncertain model parameters, so that it can simultaneously support both the uncertainty propagation and the identification of the Pareto optimal solutions. Kriging is chosen as the metamodel, and its probabilistic nature (its ability to offer a local estimate of the prediction error) is leveraged within different aspects of the framework. To reduce the number of simulations for the expensive system model, an iterative approach is established with adaptive characteristics for controlling the metamodel accuracy. At each iteration, a new metamodel is developed utilizing all available training points. A new Pareto front is then identified utilizing this surrogate model and is compared, for assessing stopping criteria, to the front that was identified in the previous iteration. This comparison utilizes explicitly the potential error associated with the metamodel predictions. If stopping criteria are not achieved, a set of refinement experiments (new training points) is identified and process proceeds to the next iteration. A hybrid design of experiments is considered for this refinement, with a dual goal of global coverage and local exploitation of regions of interest, separately identified for the design variables and the uncertain model parameters."
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

# Links (optional).
# url_pdf = "pdf/my-paper-name.pdf"
url_preprint = ""
url_doi = "https://doi.org/10.1007/s00158-018-2069-1"
url_code = ""
url_dataset = ""
url_project = ""
url_slides = ""
url_video = ""
url_poster = ""
url_source = ""

# Custom links (optional).
#   Uncomment line below to enable. For multiple links, use the form `[{...}, {...}, {...}]`.
# url_custom = [{name = "Custom Link", url = "http://example.org"}]

# Does the content use math formatting?
math = false

# Does the content use source code highlighting?
highlight = true
doi = "10.1007/s00158-018-2069-1"
# Featured image
# Place your image in the `static/img/` folder and reference its filename below, e.g. `image = "example.jpg"`.
[image]
focal_point = "Smart"
preview_only = true
