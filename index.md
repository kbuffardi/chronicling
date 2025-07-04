[comment]: # (Compile this presentation with the command below)
[comment]: # (mdslides index.md && mv index/index.html .)
[comment]: # (THEME = night)
[comment]: # (CODE_THEME = base16/zenburn)
[comment]: # (The list of themes is at https://revealjs.com/themes/)
[comment]: # (The list of code themes is at https://highlightjs.org/)
[comment]: # (Pass optional settings to reveal.js:)
[comment]: # (controls: true)
[comment]: # (keyboard: true)
[comment]: # (progress: true)
[comment]: # (width: "1024")
[comment]: # (markdown: { smartypants: true })
[comment]: # (hash: false)
[comment]: # (respondToHashChanges: false)
[comment]: # (Other settings are documented at https://revealjs.com/config/)

#### Chronicling Consistency and Parity of Contributions to Software Engineering Team Projects
----------

<sub>Kevin Buffardi, Rahul Bijoor, Aviral Kumar Srivastava, Tamanjeet Kaur Sidhu, Shalavritha Mamunooru, Aditi More</sub>

<img src="qr-chronicling.svg" alt="QR code for this presentation" width="20%">
</img>

<sub>[LearnByFailure.com/chronicling](https://learnbyfailure.com/chronicling/)</sub>

[comment]: # (!!!)

#### Software Engineering Education

- Team projects provide experiential learning
- Agile software development principles
- <u>M</u>inimum <u>V</u>iable <u>P</u>roduct
- Incremental delivery-and-discovery (Scrum sprint)
- Contributing in a team

[comment]: # (||| data-auto-animate)

#### Common Approaches to Evaluating Individuals

- Team Grades
- Peer/Self Evaluations
- Data Mining for Contribution Quantity

[comment]: # (||| data-auto-animate)

#### Unintended Outcomes

- **Team Grades**: Social loafing, responsibility hoarding
- **Peer/Self Evaluation**: Collusion, personal biases
- **Quantity**: Sacrificing quality, procrastination

[comment]: # (||| data-auto-animate)

#### What about...

- Inactive or "lone wolf" members
  - Should contribute iteratively
  - Looking for "signs of life"

[comment]: # (!!!)

#### Consistency

<img src="Consistency.png" alt="Two students who make the same number of contributions over a period of time will have the same 'frequency' of contributions, but weekly consistency will differ.">
</img>

[comment]: # (||| data-auto-animate)

#### Consistency

Data mined team repositories (via GitHub API)
- Counted artifacts authored:
  - Issue
  - Commits
  - Pull Requests
  - Code Reviews
  - Comments

[comment]: # (||| data-auto-animate)

#### Consistency

10 semesters of upper-division Software Engineering
  - 94 teams
  - 19,095 artifacts
  - 465 unique students

[comment]: # (||| data-auto-animate)

#### Consistency

<img src="artifacts_vs_week.png" alt="Looking at consistency at a per-week basis, teams tended to start making about four contributions per week, dipping lower toward the middle of the semester, and then elevating again to about five contributions per member during the final week">
</img>

[comment]: # (||| data-auto-animate)

#### (dis?) Parity

Gini Index
- Originally a measurement of economic inequality
- Can be used to compare contributions within team
- (maximum parity) 0 to 1 (maximum disparity)

[comment]: # (||| data-auto-animate)

#### (dis?) Parity

Gini Index
<img src="Gini-Coefficient.png" alt="Gini coefficient is the proportion of the area under the line of perfect equality and above the Lorenz curve, relative to the total area under the line of perfect equality" width="100%">
</img>

[comment]: # (!!!)

#### Investigating Contribution Consistency

**RQ1** Is team <u>parity</u> of <u>total</u> contributions and/or <u>consistency</u> of
contributions associated with team <u>cohesiveness</u> or lack of <u>conflict</u>?

[comment]: # (||| data-auto-animate)

#### Team Affect

End of semester CATME surveys
- Cohesiveness (M=3.79, sd=0.4)
- Conflict (M=1.5, sd=0.37)

[comment]: # (||| data-auto-animate)

#### Team Affect

Consistency (% weeks with 1+ contribution)
- M=0.48, sd=0.26
- Team Gini: M=0.32, sd=0.12

Total Artifacts
- M=37.78, sd=42.25
- Team Gini: M=0.51, sd=0.17

[comment]: # (||| data-auto-animate)

#### Team Affect

Spearman &rho; Correlations 
<img src="Correlations.png" alt="Gini coefficient of either Consistency or Total Artifacts have no significant associations with team conflict or cohensiveness" width="100%">
</img>

[comment]: # (!!!)

#### Consistency

**RQ2** What unique insights may contribution consistency provide
about teamwork that are *not already revealed by other metrics*?

[comment]: # (||| data-auto-animate)

#### Consistency

<img src="consistency_vs_frequency.png" alt="Plotting consistency versus frequency reveals some trends including students with above average frequency but below average consistency" width="100%">
</img>

[comment]: # (||| data-auto-animate)

#### Consistency

- 12% (n=55) students contributed only during a single week of the semester
  - *Not* only students who contributed at the very end (n=15)
- Maybe teams have different internal cultures
  - Rhythm of sharing contributions

[comment]: # (||| data-auto-animate)

#### Consistency

Investigating each team's **median student**:

<sub>Regression:
`Median_Artifacts + Median_Consistency + Gini_Artifacts + Gini_Consistency`
</sub>
<hr/>

`Cohesiveness = 3.514 + 0.575*Median_Consistency`

<hr/>

`Conflict = 1.645 + 0.007*Median_Artifacts - 0.727651*Median_Consistency`

[comment]: # (||| data-auto-animate)

#### Going Forward

- Alternative metrics for "consistency"
- Consistency's impact 
  - product quality
  - productivity
  - [DevOps Research and Assessment (DORA)](https://dora.dev/)
- Interventions for encouraging consistent, *impactful* contributions

[comment]: # (||| data-auto-animate)

#### Acknowledgements

- Special thanks to Sandesh Sobarad for preliminary work on GitHub API data mining
- This material is based upon work partially supported by the [National Science Foundation under grant #2337271](https://www.nsf.gov/awardsearch/showAward?AWD_ID=2337271)

[comment]: # (!!!)

#### Chronicling Consistency and Parity of Contributions to Software Engineering Team Projects

<small>This presentation is accessible at [learnbyfailure.com/chronicling/](https://learnbyfailure.com/chronicling/) and its source, along with data and analysis code is available as open source on [GitHub](https://github.com/kbuffardi/chronicling/).</small>

<img src="qr-chronicling.svg" alt="QR code for this presentation" width="30%">
</img>

<small>[Back to LearnByFailure](https://learnbyfailure.com/research/)
</small>
