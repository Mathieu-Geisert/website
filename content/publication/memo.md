+++
title = "Using a Memory of Motion to Efficiently Warm-Start a Nonlinear Predictive Controller"
date = "2017-09-15"

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["N Mansard", "A Del Prete", "M Geisert", "S Tonneau", "O Stasse"]

weights = 20

# Publication type.
# Legend:
# 0 = Uncategorized
# 1 = Conference proceedings
# 2 = Journal
# 3 = Work in progress
# 4 = Technical report
# 5 = Book
# 6 = Book chapter
publication_types = ["3"]

# Publication name and optional abbreviated version.
publication = "Submitted to *International Conference on Robotics and Automation*, IEEE."
#publication_short = "Submitted to *ICRA*"

# Abstract and optional shortened version.
abstract = "Predictive control is an efficient model-based methodology to control complex dynamical systems. In general, it boils down to the resolution at each control cycle of a large nonlinear optimization problem. A critical issue is then to provide a good guess to initialize the nonlinear solver so as to speed up convergence. This is particularly important when disturbances or changes in the environment prevent the use of the trajectory computed at the previous control cycle as initial guess. In this paper, we introduce an original and very efficient solution to automatically build this initial guess. We propose to rely on off-line computation to build an approximation of the optimal trajectories, that can be used on-line to initialize the predictive controller. To that end, we combined the use of sampling-based planning, policy learning with generic representations (such as neural networks), and direct optimal control. We first propose an algorithm to simultaneously build a kinodynamic probabilistic roadmap (PRM) and approximate value function and control policy. This algorithm quickly converges toward an approximation of the optimal state-control trajectories (along with an optimal PRM). Then, we propose two methods to store the optimal trajectories and use them to initialize the predictive controller. We experimentally show that directly storing the state-control trajectories leads the predictive controller to quickly converges (2 to 5 iterations) toward the (global) optimal solution. The results are validated in simulation with an unmanned aerial vehicle (UAV) and other dynamical systems."
abstract_short = "Predictive control is an efficient model-based methodology to control complex dynamical systems. In general, it boils down to the resolution at each control cycle of a large nonlinear optimization problem. A critical issue is then to provide a good guess to initialize the nonlinear solver so as to speed up convergence. This is particularly important when disturbances or changes in the environment prevent the use of the trajectory computed at the previous control cycle as initial guess. In this paper, we introduce an original and very efficient solution to automatically build this initial guess. We propose to rely on off-line computation to build an approximation of the optimal trajectories, that can be used on-line to initialize the predictive controller."

# Featured image thumbnail (optional)
image_preview = ""

# Is this a selected publication? (true/false)
selected = false

tags = ["Machine Learning", "Optimal Control", "UAVs"]

# Links (optional).
url_pdf = "https://hal.archives-ouvertes.fr/hal-01591373/document"
url_video = "https://youtu.be/CbyCa7aeC7k"

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

{{< youtube "CbyCa7aeC7k" >}}

