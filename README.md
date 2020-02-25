# ML Research Papers

## Description
This repository contains machine learning research papers that I read, annotate, and/or implement. 

## Installation
Make sure to have 
[Git](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git "Click here to install Git") and [Anaconda](https://www.anaconda.com/distribution/ "Click here to install Anaconda") installed. Then clone the repository using:
<pre>git clone git@github.com:eyosyaswd/ml-research-papers.git</pre>
Using Anaconda Prompt, recreate the provided environment using:
<pre>conda env create --file environment.yml</pre>
Activate the environment using:
<pre>conda activate ml-research-papers</pre>

## Updating Code
If new libraries were downloaded, use the following to update the YAML file that contains the environment:
<pre>conda env export --name ml-research-papers > environment.yml</pre>

## Directory Structure
<pre>
├── Folder
│   ├── File           &lt- Description of file.
│   ├── File           &lt- Description of file.
│   └── File           &lt- Description of file.
│
├── Folder             &lt- Description of file.
│
├── .gitignore         &lt- Ignores specified files/folders, i.e. IDE generated files/folders.
└── README.md          &lt- The top-level README for developers using this project.
</pre>
The directory structure is inspired by [Cookiecutter Data Science](https://drivendata.github.io/cookiecutter-data-science/).

## Initial Installations into Environment
<pre>
conda install python
conda install -c conda-forge jupyterlab
conda install pytorch torchvision cudatoolkit=10.1 -c pytorch
conda install -c anaconda scipy
</pre>