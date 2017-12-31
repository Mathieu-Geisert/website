+++
title = "Regularized Hierarchical Dynamic Programming"
date = "2017-04-01"

weights = 1

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["M Geisert", "A Del Prete", "N Mansard", "F Romano", "F Nori"]

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
publication = "In *Transactions on Robotics*, IEEE."
#publication_short = "In *TRO*"

# Abstract and optional shortened version.
abstract = "This paper presents a new algorithm for optimal control (OC) of nonlinear dynamical systems. The main feature of this algorithm is that it allows the specification of the control objectives as a hierarchy of tasks. Each task is described by a cost function that the algorithm tries to minimize, while not affecting the tasks of higher priority. The concept of strict priority allows for an easier and more robust specification of the control objectives, without hand-tuning of task weights. The hierarchy also makes it possible to properly regularize the behavior of each task independently. For the first time, we properly define the problem of regularizing the task cost functions in the presence of a hierarchy and propose an algorithm to compute an approximate solution. Several simulated scenarios with different robots compare our solution with other state-of-the-art methods, validating the interest of the hierarchy in OC and empirically demonstrating the importance of regularization to generate safe behaviors."
abstract_short = "This paper presents a new algorithm for optimal control (OC) of nonlinear dynamical systems. The main feature of this algorithm is that it allows the specification of the control objectives as a hierarchy of tasks. Each task is described by a cost function that the algorithm tries to minimize, while not affecting the tasks of higher priority. The concept of strict priority allows for an easier and more robust specification of the control objectives, without hand-tuning of task weights. The hierarchy also makes it possible to properly regularize the behavior of each task independently."

# Featured image thumbnail (optional)
image_preview = ""

tags = ["Optimal Control", "Hierarchy of Tasks"]

# Is this a selected publication? (true/false)
selected = true

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter the filename (excluding '.md') of your project file in `content/project/`.
#projects = ["example-external-project"]

# Links (optional).
url_pdf = "https://hal.archives-ouvertes.fr/hal-01356992v2/document"
#url_preprint = "https://hal.archives-ouvertes.fr/hal-01356992v2/document"
#url_code = "#"
#url_dataset = "#"
#url_project = "#"
#url_slides = "#"
url_video = "https://www.youtube.com/watch?v=BqAOmDvlB2Q"
#url_poster = "#"
#url_source = "#"

# Custom links (optional).
#   Uncomment line below to enable. For multiple links, use the form `[{...}, {...}, {...}]`.
#url_custom = [{name = "Youtube", url = "https://www.youtube.com/watch?v=BqAOmDvlB2Q"}]

# Does the content use math formatting?
math = true

# Does the content use source code highlighting?
highlight = true

# Featured image
# Place your image in the `static/img/` folder and reference its filename below, e.g. `image = "example.jpg"`.
#[header]
#image = "headers/bubbles-wide.jpg"
#caption = "My caption :smile:"

+++

{{< youtube "BqAOmDvlB2Q" >}}

