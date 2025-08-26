# Resources
There are *tons* of resources available online that will help you in learning statistical methods.  Here are a few that have come to my attention that may be particularly useful.

Note that this will be amended / added to as the semester goes on.  And if you have something you find valuable that isn't on here, please share it! 

## Optional, supplemental materials

### Textbooks and lecture notes
* [*Statistical Methods for Climate Scientists* by T. DelSole and M. Tippett](https://doi.org/10.1017/9781108659055)
* [*Statistical Methods in the Atmospheric Sciences* by Daniel S. Wilks](https://doi.org/10.1016/C2017-0-03921-6)
* [*Python Recipes for Earth Sciences* by Martin H. Trauth](https://link.springer.com/book/10.1007/978-3-031-07719-7).  PDF version is free.
* (older) [*Statistical Analysis in Climate Research* by Hans von Storch and Francis W. Zwiers](https://doi.org/10.1017/CBO9780511612336)
* [*Statistics for Climate Dynamics* lecture notes by D. Dommenget (free)](https://users.monash.edu.au/~dietmard/teaching/statistics-for-climate-reserach/dommenget.statistics.lecture.notes.pdf)
* FREE PDF! [/Bayesian Data Analysis/ by A. Gelman et al ](http://www.stat.columbia.edu/~gelman/book/)

### Videos
* [*Statistics for Climate Dynamics* recorded lectures (graduate-level; by D. Dommenget)](https://users.monash.edu.au/~dietmard/teaching/statistics-for-climate-reserach/lecture-videos/) 
* [GeoStatsGuy YouTube channel](https://www.youtube.com/@GeostatsGuyLectures)

### Online courses
* [Geo-Python course](https://geo-python-site.readthedocs.io/en/latest/index.html)
* [*Statistics for Climate Dynamics* course by Dietmar Dommenget, University of Monash](https://users.monash.edu.au/~dietmard/teaching/statistics-for-climate-reserach/)
* [LibreTexts statistics](https://stats.libretexts.org/)

## Computing
This course is heavily computational.  The language used is [Python](https://www.python.org/), and most graded work is submitted as executable [Jupyter notebooks](https://jupyter.org/).

### Python basics
* Official Python ("docs"): https://www.python.org/doc/ 
* Official Python beginner's guide: https://wiki.python.org/moin/BeginnersGuide

### Jupyter
* Jupyter homepage: https://jupyter.org/

### Anaconda distributions of Python
Anaconda/conda distributions of python are the strongly recommended way to use python.

* Official website: https://www.anaconda.com/
* For those on Windows and for anybody new to Python, I recommend installing the [Anaconda distribution](https://www.anaconda.com/download) on whatever computer you'll be using for this.  This installation includes the [Anaconda Navigator](https://docs.anaconda.com/free/navigator/) GUI.
* For those on MacOS or Linux with more programming experience, I recommend installing the lightweight "miniconda" distribution instead and learning to work with it from the command line: https://docs.conda.io/projects/miniconda/en/latest/

### Managing python environments and packages

#### Benefits of using Python environments rather than a single installation:
* Precise control for each class/project/etc. on exactly what packages you want installed.  (Suppose one project you're working on uses some old legacy code that requires Python 2, whereas at this point everything else runs Python 3.)
* Via conda/anaconda, automated installation of required non-python dependencies as well 
* On shared computing clusters where you don't have "root" access, ability to install packages and run things (like Jupyter!) in your home directory rather than having to go through the sysadmin
* Ability to experiment with updated versions of things without worrying about breaking your stuff.  For example, latest Python version, 3.12, just came out.  Some packages might not have support for it yet, but you can create a dedicated "python312" environment to try it out without worrying about breaking your other stuff
* Conda environments underlie modern cloud-based data science and scientific computation...Binder, cloud service providers, all of these rely on conda environments 

#### Online resources
* Managing environments using Anaconda Navigator: https://docs.anaconda.com/free/navigator/tutorials/manage-environments/ 
* Managing environments using `conda`: https://conda.io/projects/conda/en/latest/user-guide/tasks/manage-environments.html#create-env-file-manually
* Conda cheatsheet [PDF](https://docs.conda.io/projects/conda/en/latest/_downloads/843d9e0198f2a193a3484886fa28163c/conda-cheatsheet.pdf)
* `mamba` drop-in replacement for `conda` (does everything much faster and has additional nice features): https://mamba.readthedocs.io/en/latest/index.html

### Artificial intelligence tools
:::{warning}
As with any tool that is at all outside of your own brain, you **must** obey any and all rules regarding the use (or prohibition) of AI tools in your coursework, both for this course and any others.  See the [syllabus](./syllabus) for more on this, as well as the equally important concern regarding these tools being used to benefit your learning vs. a crutch that actually impedes it.
:::

* [ChatGPT](https://chat.openai.com)

### Git and Github

* ["Learn git in 15 minutes"](https://www.youtube.com/watch?v=USjZcfj8yxE) YouTube video and [accompanying notes](https://zarkom.notion.site/zarkom/Introduction-to-Git-ac396a0697704709a12b6a0e545db049)
* ["Learn Github in 20 minutes"](https://www.youtube.com/watch?v=nhNq2kIvi9s) YouTube video and [accompanying notes](https://zarkom.notion.site/zarkom/Introduction-to-GitHub-202af6f64bbd4299b15f238dcd09d2a7)
* The Github [repository](https://github.com/spencerahill/stat-methods-course) for this course website
* [Module on git and github](https://geo-python-site.readthedocs.io/en/latest/lessons/L2/git-basics.html) from the [Geo-Python course](https://geo-python-site.readthedocs.io/en/latest/index.html)
* [Git cheat sheet](https://education.github.com/git-cheat-sheet-education.pdf) created by GitHub Education

## Learning
### Spaced repetition
Storage strength vs. retrieval strength: https://fivetwelvethirteen.substack.com/p/retrieval-strength-and-storage-strength https://memorystrength.netlify.app