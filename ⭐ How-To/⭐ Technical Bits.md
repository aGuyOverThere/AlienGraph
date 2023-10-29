---
id: Technical
created_date: 07/27/2023
type: how-to
year:  2023
tags:
- 07-2023
- how-to
author: aGuyOverThere
---

----

## For Engineers, Developers, Creators, and Anyone Interested

I'm going to break down the technology stacks that are currently in-play today just to help anyone who wants to help in this project get a good bearing on what's doing what. First and foremost, this is a very simple project (right now) and heavily relies on third party (3P) software.

### Obsidian

All notes are written in markdown within the Alien Graph Obsidian Vault. The **Source of Truth** for the vault is the [Alien Graph Github Page](https://github.com/aGuyOverThere/AlienGraph). For how I setup my Obsidian instance (plugins), see [[⭐ Setup Obsidian]].

---

### Webserver

The webserver is using the [Obsidian Publish Service](https://obsidian.md/publish) as I didn't want to host and manage a webserver along with a Markdown to HTML renderer (React Gatsby for example). This is a fairly low-effort and cost effective means to simply deploy an Obsidian graph to the web which, is why I opted to use it. I know there are open source versions of Publish but, again, this is a very fast and effective way to deploy. 

---
## Future Work

There are a few things I want to do once this project has some legs and I've already started to build ad-hoc code. All code that I develop for this project will be located on [Github within the _code directory](https://github.com/aGuyOverThere/AlienGraph/tree/main/_code).

1. Scrape FOIA from specific agencies:
	1. Department of Energy
	2. Department of Defense (all military branches)
	3. National Security Agency
	4. Central Intelligence Agency
2. [NUFORC](https://nuforc.org/) Data aggregation and Analysis (automated with markdown page creation)
3. Laymen How-To writeups for the following:
	1. How to analyze video for tampering and edits. 
		1. I'm thinking a Google Collab notebook with a[ predefined ML model](https://github.com/ShobhitBansal/Video_Forgery_Detection_Using_Machine_Learning). 
		2. Metadata analysis (`exiftool`)
		3. [Optional] Steganography
	2. How to Analyze Images for tampering and edits.
	3. How to evaluate claims, third party content, other for legitimacy. 