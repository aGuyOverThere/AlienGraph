---
id: Setup
created_date: 07/09/2023
type: how-to
year:  2023
tags:
- 07-2023
- how-to
author: aGuyOverThere
---

----

[Obsidian](https://obsidian.md/) is **The** note application used for the entirety of Alien Graph. Obsidian is a powerful tool when used correctly and as such, there are a few plugins that I've installed to make tracking notes, links, and tags much easier for all of us note takers/writers.

## Plugins I Use

![[Pasted image 20230709172933.png]]
- [Templater](obsidian://show-plugin?id=templater-obsidian) - Each template in the `_templates` directly uses functions from this plugin allowing anyone to dynamically add data (i.e., date/time, ids, tags, etc.) automatically for any new note. This is extremely useful as we can use other tools to then query these notes based on this metadata allowing for expanded search and better linking. 
- [Dataview](obsidian://show-plugin?id=dataview) - **OPTIONAL** I plan to use this once things start to gain traction (many individuals contributing to AlienGraph). It provides a query language (SQL-like..) that can be used to do many things.
- [Minimal Theme Settings](obsidian://show-plugin?id=obsidian-minimal-settings) - **OPTIONAL** I use the minimal theme in Obsidian and there's a plugin that lets you customize it to your liking. This is that plugin. 

## Setup Templater

The only thing you need to do is to set your default template directory to `_templates`

1. Settings --> Templater --> Template folder location
![[Pasted image 20230709174200.png]]

## Creating a New Note

1. Open a new note in any way you like and within the directly that applied to your note type (Evidence, Intelligence, etc. ).
2. Apply the note types template in one of the following ways:
	1. Press `ctrl + p` and type `templater`. Choose "Open Insert Template Modal"
		1. ![[Pasted image 20230709174014.png]]
	2. Set and use a templater Hotkey. As you can see in the image above, mine is `ctrl + T` however, yours will be different as I've changed mine. 
3. When you've applied the template, metadata fields will have been auto-generated as well as a skeleton structure. 