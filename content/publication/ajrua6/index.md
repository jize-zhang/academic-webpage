+++
title = "Adaptive Kriging Stochastic Sampling and Density Approximation and Its Application to Rare-Event Estimation"

# Date first published.
date = "2018-04-30"

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
publication = "ASCE-ASME Journal of Risk and Uncertainty in Engineering Systems, Part A: Civil Engineering"
publication_short = "ASCE-ASME J. Risk Uncertainty Eng. Syst., Part A: Civ. Eng."

# Abstract and optional shortened version.
abstract = "This paper examines the task of approximating or generating samples according to a target probability distribution when this distribution is expressed as a function of the response of an engineering system. Frequently such approximation is performed in a sequential manner, using a series of intermediate densities that converge to the target density and may require a large number of evaluations of the system response, which for applications involving complex numerical models creates a significant computational burden. To alleviate this burden an adaptive Kriging stochastic sampling and density approximation framework (AK-SSD) is developed in this work. The metamodel approximates the system response vector, whereas the adaptive characteristics are established through an iterative approach. At the end of each iteration, the target density, approximated through the current metamodel, is compared to the density established at the previous iteration, using the Hellinger distance as a comparison metric. If convergence has not been achieved, then additional simulation experiments are performed to inform the metamodel development, through a sample-based design of experiments that balances between the improvement of the metamodel accuracy and the addition of experiments in regions of importance for the stochastic sampling. These regions are defined by considering both the target density and any intermediate densities. The process then moves to the next iteration, with an improved metamodel developed using all the available simulation experiments. Although the theoretical discussions are general, the emphasis is placed on rare-event simulation. For this application, once the target density is approximated (first stage), it is used (second stage) as an importance sampling density for estimating the rare-event likelihood. For the second stage, use of either the metamodel or the exact numerical model is examined."
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
url_doi = "https://doi.org/10.1061/AJRUA6.0000969"
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
doi = "10.1061/AJRUA6.0000969"
# Featured image
# Place your image in the `static/img/` folder and reference its filename below, e.g. `image = "example.jpg"`.
[image]
caption = "Fig. 1: Indirect inference model calibration."
focal_point = "Top"
preview_only = true
+++
