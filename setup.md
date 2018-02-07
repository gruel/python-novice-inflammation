---
layout: page
title: Setup
permalink: /setup/
---

In preparation for this lesson, you will need to download one zipped file and place it in the specified folder:

1. Make a new folder in your Desktop called `python-novice-inflammation`.
2. Download [python-novice-inflammation-data.zip][zipfile1] and move the file to this folder.
3. If the file aren't unzipped yet, double-click to unzip it. You should end up with 
one new folder called `data`.
4. To get started, go into the `data` folder from the Unix shell with:

	~~~
	$ cd
	$ cd Desktop/python-novice-inflammation/data
	~~~
	{: .source}

	If you will be using the Jupyter (IPython) notebook for the lesson,
	you should have already
	[installed Anaconda](http://swcarpentry.github.io/workshop-template/#setup)
	which includes the notebook.

6. To start the notebook server, open a terminal or git bash and type the command:

	~~~
	$ jupyter notebook
	~~~
	{: .source}

7. Then create a new notebook using the drop-down menu on the right to select 'Python 3 notebook':

	![](../fig/new-notebook.png)

[zipfile1]: {{ page.root }}/data/python-novice-inflammation-data.zip
[zipfile2]: {{ page.root }}/code/python-novice-inflammation-code.zip
