---
permalink: /
title: "Junwon Seo's personal website"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---
Welcome to my website! I am a Ph.D. Candiate in the Department of [Materials Science and Engineering](https://www.materials.cmu.edu/) at [Carnegie Mellon](https://www.cmu.edu/) advised by Professor [Anthony Rollett](https://en.wikipedia.org/wiki/Anthony_Rollett). 
-----
I am an ethusiastic researcher of Metal Additive Manufacturing [(AM)](https://en.wikipedia.org/wiki/3D_printing), specifically Powder Bed Fusion [(PBF)](https://en.wikipedia.org/wiki/Selective_laser_melting) of Nickel-based Superalloys. My goal is to make AM reliable and approachable enough that it can be an eco-friendly manufacturing method for everyday things.

Prior to joining Carnegie Mellon, I was an undergraduate intern at [IBS](https://www.ibs.re.kr/eng.do) (the Institute for Basic Science) in Ulsan, Korea, a post-graduate resaercher at [Max Planck Institute](https://www.mpg.de/en) in Dresden, Germany, and a machine learning Intern at [KIST](https://www.kist.re.kr/eng/index.do) (Korea Institute of Science and Technology) in Seoul, Korea.

I graduated from [Korea Universuty](https://www.korea.edu/sites/en/index.do) Department of [Materials Science and Engineering](https://mse.korea.ac.kr/index.php)), where I served as the president of an academic society [KUMUS](https://mse.korea.ac.kr/bbs/board.php?bo_table=sub5_7), student representative of my class of 2020, and a member a Street Dance team [KUDT](https://www.youtube.com/c/KUDTdancers)!

Microstructure Characterization, Energy Applications, Computational Materials Science, Computer Vision, Large Language Models

Materials Science and Machine Learning
------
For site content, there is one markdown file for each type of content, which are stored in directories like _publications, _talks, _posts, _teaching, or _pages. For example, each talk is a markdown file in the [_talks directory](https://github.com/academicpages/academicpages.github.io/tree/master/_talks). At the top of each markdown file is structured data in YAML about the talk, which the theme will parse to do lots of cool stuff. The same structured data about a talk is used to generate the list of talks on the [Talks page](https://academicpages.github.io/talks), each [individual page](https://academicpages.github.io/talks/2012-03-01-talk-1) for specific talks, the talks section for the [CV page](https://academicpages.github.io/cv), and the [map of places you've given a talk](https://academicpages.github.io/talkmap.html) (if you run this [python file](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.py) or [Jupyter notebook](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.ipynb), which creates the HTML for the map based on the contents of the _talks directory).


**Markdown generator**
I have also created [a set of Jupyter notebooks](https://github.com/academicpages/academicpages.github.io/tree/master/markdown_generator
) that converts a CSV containing structured data about talks or presentations into individual markdown files that will be properly formatted for the academicpages template. The sample CSVs in that directory are the ones I used to create my own personal website at stuartgeiger.com. My usual workflow is that I keep a spreadsheet of my publications and talks, then run the code in these notebooks to generate the markdown files, then commit and push them to the GitHub repository.

How to edit your site's GitHub repository
------
Many people use a git client to create files on their local computer and then push them to GitHub's servers. If you are not familiar with git, you can directly edit these configuration and markdown files directly in the github.com interface. Navigate to a file (like [this one](https://github.com/academicpages/academicpages.github.io/blob/master/_talks/2012-03-01-talk-1.md) and click the pencil icon in the top right of the content preview (to the right of the "Raw | Blame | History" buttons). You can delete a file by clicking the trashcan icon to the right of the pencil icon. You can also create new files or upload files by navigating to a directory and clicking the "Create new file" or "Upload files" buttons. 

Example: editing a markdown file for a talk
![Editing a markdown file for a talk](/images/editing-talk.png)
