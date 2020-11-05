---
layout: single
title:  "Generate a word cloud from a PDF file"
date:   2020-11-04
categories: 
  - datascience
  - data
  - statistics
header:
  teaser: " /images/biogas.jpeg"

---

Including visuals to emphasize an information and summarize a document is always nice, but not many of us can do this in a time efficient manner. 

Python makes **word cloud generation** a **simple and quick** process. 

Let's go through all the steps to get that fancy word cloud for tomorrow's presentation.

<ol>
<li> Download Python </li>
<li> If you do not want to use python, you can install anaconda to access Jupyter notebook</li>
<li> Open terminal through clicking on start -> type: cmd -> press enter</li>
<li> Install required packages by typing into terminal the following: </li>
</ol>

  ``` 
  py.exe -m pip install --user numpy scipy matplotlib ipython jupyter pandas sympy nose pdfminer textblob
  ```
<ol start="5">
<li> Create a folder through Jupyter Notebook where you would like to store all of your files Note: I prefer making it on my desktop</li>
<li> Save a) the pdf of choice b) the python file (opened through Jupyter notebook) in that same folder</li>
<li>Copy the code attached</li>
<li>Save a mask image as a template for the wordcloud</li>
<li>Run the code</li>
<li>Voila!</li>
</ol>


