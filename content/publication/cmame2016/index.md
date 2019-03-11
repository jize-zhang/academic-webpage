+++
title = "Sequential approximate optimization for design under uncertainty problems utilizing Kriging metamodeling in augmented input space"

# Date first published.
date = "2016-11-03"

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Jize Zhang", "Alexandros Taflanidis", "Juan Camilo Medina"]

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
publication = "Computer Methods in Applied Mechanics and Engineering"
publication_short = "CMAME"

# Abstract and optional shortened version.
abstract = "This paper discusses design-under-uncertainty problems that employ a probabilistic performance as objective function and consider its estimation through stochastic (i.e., Monte Carlo) simulation. This setting facilitates a great modeling flexibility but has an associated high computational burden, and a framework relying on kriging surrogate modeling is proposed here to address this challenge. The metamodel is formulated to approximate the system response (metamodel output) with respect to both the design variables and the uncertain model parameters (augmented metamodel input), so that it can simultaneously support the uncertainty propagation and the design optimization, adopting a sequential approximate optimization (SAO) strategy for the latter. At each SAO cycle a sub-region of the design space is defined and a kriging metamodel is built exploiting information from the previous SAO cycle to improve accuracy. Within a stochastic simulation setting this metamodel is first utilized to approximate the system performance when estimating the objective function for specific design configurations. This information is subsequently used to search for a local optimum within the considered design sub-region till convergence to an interior point or the boundary of the region is established, prompting the termination of the current SAO cycle. When convergence to the boundary is established, the quality of the obtained solution is examined and if desired criteria are satisfied the next cycle moves to a new sub-region and the process is repeated till convergence is established. Else, an adaptive refinement of the design of experiments is established by adding optimally selected new support points for informing the metamodel development, and the next SAO cycle remains in the current sub-region. Through this approach an adaptive control for the accuracy of the metamodel is achieved, minimizing the number of simulations for the expensive system model."
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
url_doi = "https://doi.org/10.1016/j.cma.2016.10.042"
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
doi = "10.1016/j.cma.2016.10.042"
# Featured image
# Place your image in the `static/img/` folder and reference its filename below, e.g. `image = "example.jpg"`.
[image]
focal_point = "Smart"
preview_only = true
+++
