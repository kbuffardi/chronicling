# Chronicling Consistency and Parity of Contributions to Software Engineering Team Projects, 2025

This repository contains the online presentation:

"Chronicling Consistency and Parity of Contributions to Software Engineering Team Projects" by Kevin Buffardi, Rahul Bijoor, Aviral Kumar Srivastava, Tamanjeet Kaur Sidhu, Shalavritha Mamunooru, Aditi More

The full paper is available on [ACM Digital Library as published at ITiCSE'25](https://dl.acm.org/doi/abs/10.1145/3724363.3729039).

The paper's full citation is:
```
Kevin Buffardi, Rahul Bijoor, Aviral Kumar Srivastava, Tamanjeet Kaur
Sidhu, Shalavritha Mamunooru, and Aditi More. 2025. Chronicling Consistency
and Parity of Contributions to Software Engineering Team Projects.
In Proceedings of the 30th ACM Conference on Innovation and Technology in
Computer Science Education V. 1 (ITiCSE 2025), June 27-July 2, 2025, Nijmegen,
Netherlands. ACM, New York, NY, USA, 7 pages. https://doi.org/10.1145/
3724363.3729039
```

or in BibTex format:
```
@inproceedings{10.1145/3724363.3729039,
author = {Buffardi, Kevin and Bijoor, Rahul and Srivastava, Aviral Kumar and Sidhu, Tamanjeet Kaur and Mamunooru, Shalavritha and More, Aditi},
title = {Chronicling Consistency and Parity of Contributions to Software Engineering Team Projects},
year = {2025},
isbn = {9798400715679},
publisher = {Association for Computing Machinery},
address = {New York, NY, USA},
url = {https://doi.org/10.1145/3724363.3729039},
doi = {10.1145/3724363.3729039},
abstract = {In Software Engineering courses, students typically work in groups to collaborate on team projects. However, contributions to these projects are not always fairly distributed across team members and sometimes individuals are less consistent at making contributions over an academic term. This paper investigates discrepancies in the consistency of each member's contributions to software engineering teams. We studied 94 software engineering teams from undergraduate software engineering courses and gathered evidence of each member's (n=465) activities on GitHub, including commits, pull requests, issues, code reviews, and comments. We analyzed whether each member exhibited any of these activities for each week of the academic term to measure the consistency of their contributions. We calculated the (dis)parity of how consistently each team member made contributions using the Gini coefficient, which measures (in)equity within groups. Each team also self-reported their frequency of conflicts and cohesiveness toward a common goal. This exploratory study investigates the relationship between parity among teammates' consistency and the team's overall cohesiveness and lack of conflict. While parity of consistency varied between teams, there was no association between it and teams' cohesiveness or conflicts. However, median team consistency was a significant predictor of team cohesiveness and a lack of conflicts.},
booktitle = {Proceedings of the 30th ACM Conference on Innovation and Technology in Computer Science Education V. 1},
pages = {562–568},
numpages = {7},
keywords = {collaboration, consistency, gini index, git, github, individual contributions, software development, teamwork, time},
location = {Nijmegen, Netherlands},
series = {ITiCSE 2025}
}
```


## Presentation

The slides can be viewed in a web browser by opening [index.html](index.html) or as hosted at [learnbyfailure.com/chronicling/](https://learnbyfailure.com/chronicling/).

## Rebuild HTML

To convert the markdown into HTML, run the following command:

```
mdslides index.md && mv index/index.html .
```

For markdown formatting for these slides, see [markdown-slides](https://github.com/dadoomer/markdown-slides)