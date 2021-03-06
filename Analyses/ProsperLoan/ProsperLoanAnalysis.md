---
layout: post
title: ProsperLoanAnalysis
permalink: /analyses/ProsperLoanAnalysis

---

# Prosper Loan Analysis

[Github link](https://github.com/AhmedOmarEissa/ProsperLoanAnalysis)


## Dataset

The data consists of information regarding loan requests provided by prosper, The dataset can be found [here](https://www.kaggle.com/yousuf28/prosper-loan),
with feature documentation available [here](https://docs.google.com/spreadsheets/d/1gDyi_L4UvIrLTEC6Wri5nbaMmkGmLQBk-Yx3z0XDEtI/edit#gid=0).


## Summary of Findings

In the exploration, I tracked the loan features change over the years, focusing on the impact after 2008 financial crisis. After 2008 there was a sharp decline in # of loans and the amount of money lended, then a ste increase in both metircs, reaching the maximum by 2013, also, there was an increase in loan rate after 2008, which is expected, then it started to decline after 2011.Loan defaulted was the highest in 2006, started to decline sharply since 2009 with more completed loans, because after 2008 the debt consolidation is the # 1 reason for asking for loans, by 2013 it represented around 80% of the # of loans.

I digged deeper in the debt consolidation loans, trying to understand when people tend to request debt consolidation loan. Non debt consolidation seems bi-modal, which make sense, people don't take loans because either they don't have open credit items or they don't like the idea and starting from 7 open items we see an increase in the % of dept consolidation.

[Notebook](./ProsperLoanAnalysis.html)
[Slides](./Slides.Slides.html)


