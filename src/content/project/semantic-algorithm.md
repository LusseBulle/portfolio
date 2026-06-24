---
title: "Semantic Sliding-Window Algorithm for PDF Annotations"
description: "Evaluating semantic NLP models against lexical baselines to reliably transfer document annotations across versions"
pubDate: Jun 12 2026
role: "Lead Developer (Solo Project)"
tags:
  - university
  - nlp
  - python
  - streamlit
---
## Thesis
For my [bachelor's thesis](https://liu.diva-portal.org/smash/record.jsf?pid=diva2%3A2070933&dswid=2524), I researched methods of  transferring annotations across different versions of PDF documents. When documents are revised, manual re-annotation is time-consuming. My research focused on automating this recovery process by pivoting away from traditional lexical matching in favor of a semantic approach.

### Method and framework
The core of the project involved evaluating a semantically-based sliding-window algorithm against a lexical baseline, this experimental framework was built in Python. This framework encompasses everything from the underlying algorithms and data fetching pipelines to the execution and measurement of the experiment itself.

## Proof-of-Concept Tool
Following the finalization of the research report, the findings within were used to create a [tangible proof-of-concept](https://gitlab.liu.se/lucer590/annotation-transfer). 

Using Streamlit for the UI, I created a functional recovery tool that demonstrates the semantic algorithm in action. Due to the tool being an artifact of the research conducted, specific algorithmic limitations were intentionally retained. These limitations serve as a baseline for potential optimisation and improvement by future students.