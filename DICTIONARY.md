# *Epic Impact*: Data Dictionary

This file describes the variables and values in the data set contained in this
repository, `epic-data-full.csv`. The data are a combination of metadata about
the U.S. circuit and district court decisions citing *Epic Systems Corp. v.
Lewis* in 2018, and categorizations assigned manually for the purposes of
reporting the story *Epic Impact*, published in February 2019 by the *National
Law Journal*. 

## Decision Metadata
`decision_id`  
incrementally assigned id code (int)

`case_name_short`  
short version of the case caption (string)

`case_name_long`  
long version of the case caption (string)

`jurisdiction_code`  
short code for the deciding court (string)

`jurisdiction_long`  
full name of the deciding court (string)

`court_type`  
either circuit or district (string)

`decide_date`  
date decision was made (ISO format)

`casetext_url`  
URL to decision on Casetext website

## Decision categorical data
`class_action`  
proposed collective or class action, or not (boolean)

`case_type`  
general category based on the facts and legal claims alleged; only one per case
(string)

`legal_issue`  
binary category: was the main legal issue before the court whether the case
should be compelled to arbitration, or "other" (string)

`cite_context`  
was the citation to *Epic* used to support the court's ultimate decision
("supportive"), made in passing ("in_passing"), or did the court distinguish
*Epic*'s applicability to the facts before it (string)

`cite_excerpt`  
an excerpt in which the court cites or refers to *Epic* (string)

`outcome_code`  
the court compel arbitration, deny the enforcement of the arbitration
agreement, revive the arbitration issue, or something else? (string)

`decision_favor`  
which party's favor was the issue decided, plaintiff ("ptf"), defendant
("def") or mixed (string)
