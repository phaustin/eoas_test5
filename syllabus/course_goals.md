---
jupyter:
  jupytext:
    formats: ipynb,md
    text_representation:
      extension: .md
      format_name: markdown
      format_version: '1.3'
      jupytext_version: 1.10.3
  kernelspec:
    display_name: Python 3 (ipykernel)
    language: python
    name: python3
---

# Course Syllabus

## Old Syllabus 

### Course Level Learning Goals

1.  Students will write computer programs to model and analyze data in the solid earth, atmospheric,
 and oceanographic sciences. This requires:

2.  Breaking problems into logical steps using flowcharts and pseudocode to specify algorithms: Operation; repetition; decision and input/output steps; computer math

3.  Writing and debugging MATLAB code to correctly implement algorithms: syntax and datastructures; debugging strategies

4.  Modifying existing MATLAB code,  using the elements of good programming style,  to make  it  more  efficient,  readable,  and  documented  for  future  use:  naming  conventions;appropriate syntax;  structures;  modularization using functions;  using built-in functions;code reuse; good documentation  practices; vectorization of loop operations

5.  Creating scientifically informative and visually appealing plots (scatterplots, time series,contours,  multiple subplots, legends)




##  New Syllabus Brainstorming 

HARD SKILLS:

- differentiate between and know the basic operations related to
  string, int, float, boolean, none, list, set, tuple, dictionary
- manipulate numpy array, pandas dataframe(?)
- make pretty plots
- define functions so you DRY (dont repeat yourself)
- use a shell or terminal to do stuff
- debug code
- google your way out of problems -- this is important
- develop a workflow that works BEYOND eosc211 -- i do all my hw assignments now in jupyter...

SOFT SKILLS:

- be confident going from earth/ocean/atmosphere -> numerical dataset -> code -> scientific conclusion
- appreciate computational principles and apply some of them: abstraction, efficiency, modularization
- understand the relationship between GUIs, high level languages, low level languages, assembly code
- foster an appropriate desire for efficient/elegant/pythonic code and fear/hatred of cludges without going overboard
- appreciate that there are many ways to solve a single problem and some are better than others
- confidence with viewing/using a computer like a programmer - shells/terminals, code, vocabulary like 'back end,' 'gui'

BIG PRINCIPLES:
- coding is hard and i feel like i have no idea what im doing and everyone is smarter than me. thats fine
- DRY and YANGNI
- Make it look good
- Keep your hard drive organized just like you would a lab bench
- namespaces are one honking great idea -- lets do more of those




 week | readings | worksheets | lab
 ---  |--- |--- |   --- |
 1| | none | none
 2| `01-Orientation/01_01-Why-Python.md` <br> `02-Jupyter-Notebooks/02_05-The-Jupyter-Notebook-Interface.md` (optional) <br> all of `04-Data-Types-and-Variables` | algorithm design, intro to python, built in functions, data types | intro to jupyterlab (not yet created)
 3| `05-NumPy-and-Arrays/05_03-Python-Lists-and-NumPy-Arrays.md` <br> `05-NumPy-and-Arrays/05_04-Array-Creation.md` (optional) <br> `05-NumPy-and-Arrays/05_05-Array-Indexing.md` <br> `05-NumPy-and-Arrays/05_06-Array-Slicing.md` <br> `05_07-Array-Opperations.md` | intro to numpy arrays, built in functions, slicing *ZOP*| matplotlib, scientific figures, [import, input, process, output], array manipulation
 4| `06_01-What-is-Matplotlib.md` <br> `06-Plotting-with-Matplotlib/06_03-Line-Plots.md` <br> `06-Plotting-with-Matplotlib/06_05-Multi-Line-Plots.md` <br> `06-Plotting-with-Matplotlib/06_11-Plot-Annotations.md` <br> `06-Plotting-with-Matplotlib/06_14-Contour-Plots.md` <br> *all of chapter 6 is a useful resource for this course/future* |  DNE | math, code structuring, plt subplots
 5| 8-1 to 8-4 |  logic, `if elif else` | plt.annotate(), f strings, type casting, user input
 5.5  | | Assignment 1
 6| 9-0 to 9-2 | loops | filtering with running mean/median, implemented with loops (slow)
 7|  | MIDTERM
 8| 7-0 to 7-4, 7-6 and 7-7 (optional) | functions | re-do lab 6 with functions
 9|  | debugging and error types (off by one, fencepost) | go through a "large" functional program, using dictionaries, `*args, **kwargs` 
 10|  | dictionaries and f strings | DNE
 11|  | vectorization and speed | interpolation with scipy
 12|  | vectorization practice, file IO (csv) | DNE
 13|  | review, linear algebra | DNE
 
## things that arent in e211 that should be(?):

* formal discussion of objects
* pandas
* xarray
* geopandas -- for the gis students
* scipy for linalg, integrations
* DIY python, how to set up your own workflow
* shell tutorial
* timeit module
* numba?
* intro to git
* file IO with python
* datetime




