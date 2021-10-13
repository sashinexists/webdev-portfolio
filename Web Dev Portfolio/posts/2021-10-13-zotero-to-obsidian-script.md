---
title: "Zotero-to-Obsidian scrip"
published_date: "2021-10-13 21:35:57 +0000"
layout: post.liquid
is_draft: false
data: {
    banner_url: "/images/zotero-to-obsidian_screenshot.png",
    brief: "A script that converts data about your resources from Zotero to Obsidian"
}
---
### About this Project
I wrote this script for my own personal use but shared it through Github so anyone else can also benefit.

[Zotero](https://zotero.org) is an open-source reference manager that is used widely by academics across the world. It allows you to keep track of the literature you use and the notes you take on it. It also has features such as being able to generate citations and bibliographies in a single click. When you add a paper, article or book on Zotero it is automatically able to fetch relevant data including the authors, publication date, brief and journals.

[Obsidian](https://obsidian.md) is my favourite app or all time. I am currently writing this text in it right now. I use it to write anything that needs to be written and to organise everything in my life. I have written more about it [here](https://sashinexists.com/letter/notes-about-notes-bonus-notes-included/).

This script that I wrote simply takes a look at all my resources in Zotero and generates markdown files that can be viewed and linked to from Obsidian.

So, I have a separate markdown plaintext file for each of the books, articles, paper etc that I have read and can reference them easily in any of the notes I write.

-----
# The Tech Behind it
This script was written entirely in Rust. It looks at the data from Zotero, which is stored as a JSON file it then reads a set of markdown templates that I have made and writes the Zotero data into the templates.