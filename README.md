# README: 'Epic' Impact

By [Ben Hancock](https://www.law.com/author/profile/Ben-Hancock/)

This GitHub repository is part of a data journalism project by ALM Media data
editor Ben Hancock and *National Law Journal* labor law reporter Erin Mulvaney
to assess the impact of *Epic Systems Corp. v. Lewis*, a May 2018 decision by
the U.S.  Supreme Court that centered on the enforceability of mandatory
workplace arbitration agreements. In collaboration with
[Casetext](https://casetext.com/), we identified and categorized nearly a
hundred U.S. district and appellate court decisions that cited *Epic* in
calendar year 2018, in order to quantify the scope of Supreme Court's impact on
this issue in the months after it was handed down. The story was [published on
the NLJ website in February
2019](https://www.law.com/nationallawjournal/2019/02/28/epic-impact-how-a-major-scotus-decision-in-favor-of-arbitration-is-shaping-the-landscape-for-workplace-lawsuits),
and was the cover story for the NLJ's March 2019 print magazine.

In this repository, you will find the data set we assembled to report this
story, a data dictionary explaining the different variables and codes
(DICTIONARY.md), and a Jupyter Notebook that shows how we did our analysis. Our
goal in presenting this to our audience is to "show our work" and give greater
transparency into the approach we took in reporting an issue with wide public
interest and significance. 

## Methodology
We reviewed nearly a hundred decisions by U.S. federal courts that were
identified by Casetext’s legal research tool as citing *Epic Systems* in 2018.
If there was more than one such decision handed down in the same case, we
excluded all but one in favor of the decision that dealt most closely with
arbitration. In total, we identified 17 circuit court decisions and 75 district
court decisions, some of which were marked as unpublished.  

In order to analyze this corpus of cases, we manually categorized the opinions
along some key metrics. These included whether the case was a proposed class or
collective action, case type, and whether arbitration was the main issue before
the court in the decision. Selecting a case type was often the most challenging
task, as many cases involve a slew of legal claims. For example, some cases
involving allegations of gender discrimination may also allege general
wage-and-hour law violations. For such cases, our rule was that if
discrimination or sexual harassment claims were present, they would prevail for
the purpose of categorization. 

A brief note about what we can and cannot learn about the impact of *Epic*
strictly from the data we gathered: First, we cannot conclude that *Epic*
directly caused cases to be compelled to arbitration at a higher rate than
before. We did not gather data on how similar cases were decided prior to *Epic*,
and so do not purport to have a baseline for comparison. It’s also difficult to
generalize the degree to which *Epic* was the sole or the most important factor
in a body of cases being compelled to arbitration, given the unique
fact-patterns in much of the litigation.  

But what we can say is that in the majority of cases where arbitration was the
key issue before the court in a case citing *Epic*, arbitration won out, and
that for cases involving workplace-related claims, that statistic was even more
pronounced.

## Questions & Comments 
If you have questions or comments about our categorization or overall
methodology, please feel free to contact ALM data editor Ben Hancock at
bhancock@alm.com.
