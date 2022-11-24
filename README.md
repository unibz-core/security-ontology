## ROSE: A Reference Ontology for Security Engineering

ROSE is a well-founded reference ontology, specified in OntoUML modeling language, that characterizes the concept of security mechanism and explains how it this notion is related to value, risk, and prevention.

PURL: https://purl.org/security-ontology

## Project Struture

* [/ontouml](/ontouml) contains files related to the conceptual version of ROSE, which is represented in OntoUML.
* [/owl](/owl) contains files related to the [gUFO-based](https://nemo-ufes.github.io/gufo/) implementation of ROSE, represented in OWL.

## Reusing .vpp files

* To open and edit .vpp files, use [Visual Paradigm](https://www.visual-paradigm.com)
* To open and edit .ttl files, use [Protégé](https://protege.stanford.edu/)

## Built with

* [Visual Paradigm](https://www.visual-paradigm.com) - a UML CASE tool that offers a [free community edition version](https://www.visual-paradigm.com/download/community.jsp)
* The [OntoUML Plugin](https://github.com/OntoUML/ontouml-vp-plugin) for Visual Paradigm

## Video presentation

[<img src="https://i.ytimg.com/vi/ZK8onlp7j0w/maxresdefault.jpg" width="50%">](https://www.youtube.com/watch?v=ZK8onlp7j0w "Watch the video")

## Authors

* **[Ítalo Oliveira](https://sites.google.com/view/italojsoliveira)** - Free University of Bozen-Bolzano, Bolzano, Italy
* **[Tiago Prince Sales](https://www.inf.unibz.it/~tpsales/)** - Free University of Bozen-Bolzano, Bolzano, Italy
* **[Riccardo Baratella](https://scholar.google.it/citations?user=iVvfMXcAAAAJ)** - Free University of Bozen-Bolzano, Bolzano, Italy
* **[Mattia Fumagalli](http://www.mattspace.net/)** - Free University of Bozen-Bolzano, Bolzano, Italy
* **[Giancarlo Guizzardi](https://www.unibz.it/en/faculties/computer-science/academic-staff/person/37428-giancarlo-guizzardi)** - Free University of Bozen-Bolzano, Bolzano, Italy

## References

- Baratella, R., Fumagalli, M., Oliveira, Í., Guizzardi, G. (2022). Understanding and Modeling Prevention. In: Guizzardi, R., Ralyté, J., Franch, X. (eds) Research Challenges in Information Science. RCIS 2022. Lecture Notes in Business Information Processing, vol 446. Springer, Cham. https://doi.org/10.1007/978-3-031-05760-1_23
- Oliveira, Í., Sales, T.P., Baratella, R., Fumagalli, M., Guizzardi, G. (2022). An Ontology of Security from a Risk Treatment Perspective. In: Ralyté, J., Chakravarthy, S., Mohania, M., Jeusfeld, M.A., Karlapalem, K. (eds) Conceptual Modeling. ER 2022. Lecture Notes in Computer Science, vol 13607. Springer, Cham. https://doi.org/10.1007/978-3-031-17995-2_26

## Errata

- In ROSE, the cardinality of << characterization >> relation between Intention and subjects (Risk Subject, Attacker, Protected Subject, and Security Designer) should be 0...1, instead of 1, as it is written in the ER paper. This repository contains the corrected version.
