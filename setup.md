---
layout: page
title: Setup
permalink: /setup/
---

In preparation for this lesson, you will need to download a zip file of data.

# Windows instructions

1. Download [python-novice-inflammation-data.zip][zipfile1] and move the file to `C:\Work`.
If there are already files in `C:\Work`, just go ahead and delete them first.

2. Extract the contents of the zip file (right click, Extract All).
Double clicking on the file simply previews the files - it doesn't extract them.
	![](../fig/extract.png)

3. If all goes well, you should see a `data` folder within your extracted folder.
	![](../fig/extracted.png)

4. From the Start menu, select `Anaconda Prompt`, and issue the following commands
to start the notebook server:
	```
	cd C:\Work\python-novice-inflammation-data\data
	jupyter notebook
	```
	{: .source}
	![](../fig/anaconda-prompt.png)

5. Then create a new notebook using the drop-down menu on the right to select 'Python 3 notebook':
	![](../fig/new-notebook.png)


# Linux instructions

1. Make a new folder in your Desktop called `python-novice-inflammation`.
2. Download [python-novice-inflammation-data.zip][zipfile1] and move the file to this folder.
3. Extract the zip archive. You should end up with 
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

5. To start the notebook server, open a terminal or git bash and type the command:

	~~~
	$ jupyter notebook
	~~~
	{: .source}

6. Create a new notebook using the drop-down menu on the right to select 'Python 3 notebook'.

[zipfile1]: {{ page.root }}/data/python-novice-inflammation-data.zip
