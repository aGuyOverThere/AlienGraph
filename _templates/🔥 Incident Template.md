---
id: <% tp.file.title.split(" ")[0] %>
created_date: <% tp.file.creation_date('MM/DD/YYYY') %>
type: incident
year:  <% tp.file.creation_date('YYYY') %>
tags:
- <% tp.file.creation_date('MM-YYYY') %>
- incident
author:
---

----
<% await tp.file.move("🔥 Incidents/" + "🔥 " + tp.file.title) %>
## Overview

- **Source**: (reddit post, FOIA, declassification, leak, etc.)
- **Incident Type**: (encounter, material, UAP)
- **Incident Date**: Actual date of the incident
- **Reported Date**: Date in which the incident was reported. 
- **Author**: the author of the intelligence or unknown
- **Location**:
- **Trust Score:** [Google Sheets Scoring Matrix](https://docs.google.com/spreadsheets/d/1CUarxE7P1cPwgWXwJzzeWnZGm1c6Wp2Ttazdt3VPM_s/edit?usp=sharing)

<details>
<summary><b>Trust Score Analysis</b></summary>
<IMG src="https://publish-01.obsidian.md/access/1c31a6f93f82a49b0a9eb31193d6cdec/_images/" alt="Trust Score"/>
</details>

## Summary

Summarize the information in just a few sentences,

## Claims and Assertions

What is the intelligence stating? Do we have evidence for such claims/assertions? 

## Media

## References

