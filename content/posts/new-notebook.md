---
title: "New Notebook"
date: 2020-09-27T18:43:55-04:00
summary: Wow - new notebook at last!
---
After weeks of prep work, I finally have a new 
static site notebook for martial arts.  I hope to make this 
a very good notebook because I have tried a number of times
in the past to keep a notebook, but wasn't able to.

My previous attempts at a notebook floundered on several things.  One was a 
lack of a reliable platform.  For example, I lost a year's notes
due to a hard drive crash.  There were other problems, but
let's not dwell on it.

This notebook has several parts:

1.  A Hugo project on my Mac *hugo-notebook* for the landing page *hugo-notebook.com*.
2.  A second Mac project, *argon*, for martial arts.
3.  A repo on github for each of the above.  
4.  Amazon S3 storage for deployment.

The github repos have travis ci scripts to rebuild the 
S3 sites whenever anything changes in the repo.  

When I'm working on my martial arts notebook, I make additions and edits to the Mac version,
then upload them to github to trigger a rebuild and deploy.  Meanwhile,
I can view my changes on the Mac by using the hugo serve command and going to localhost:1313/argon
in my browser.
