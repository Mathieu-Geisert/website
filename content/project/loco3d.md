+++
# Date this page was created.
date = "2016-04-27"

# Project title.
title = "Loco3d"

# Project summary to display on homepage.
summary = "A fully automatic pipeline for multicontact locomotion on uneven terrains."

# Optional image to display on homepage (relative to `static/img/` folder).
image_preview = "loco3d_graphGeneral.png"

# Tags: can be used for filtering projects.
tags = ["Humanoid Robotics"]

# Optional external URL for project (replaces project detail page).
external_link = ""

# Does the project detail page use math formatting?
math = false

# Optional featured image (relative to `static/img/` folder).
[header]
image = "loco3d_graphGeneral.png"
caption = ""

+++

The *Loco3d* project is a project developed in the *Gepetto* team that aims to build a full pipeline to generate locomotion movements in a complex environment. Such pipeline have been also seen in the case of a quadruped robot for the DARPA Learning Locomotion project.<br>

To overcome the different difficulties of humanoid locomotion, the locomotion problem is solved with a succession of planners/controllers:<br>
<ul>
	[<li> Planning of an approximate path for the center of the robot.</li>
	<li> Planning of the contacts.</li>](https://hal.archives-ouvertes.fr/lirmm-01149666/document)
	[<li> Planning of a precise trajectory for the center of mass. </li>] (https://hal.archives-ouvertes.fr/hal-01520248/document)
	[<li> Control of all motors. </li>] (https://www.researchgate.net/project/Compliant-feedback-control-of-legged-robots)
</ul>

<br>
[RSS Workshop on Challenges in Dynamic Legged Locomotion, Jul 2017] (https://hal.archives-ouvertes.fr/hal-01543060/document)