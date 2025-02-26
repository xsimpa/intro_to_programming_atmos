# Syllabus

German: *Lehrveranstaltungskonzept*. **Please read it carefully at the beginning of the class, and return to it as often as necessary.**

```{warning}

It is the first time I'm giving these lecture notes. The syllabus is likely change in the course of the semester, but each change will be communicated in class. It is your responsibility to attend the class to stay informed about any changes.

```

## Learning outcomes

After successful completion of the course, you will:
- be able to read and write programs in the Python programming language.
- understand how to use basic programming control flows (branches and loops) and data structures (numbers and collections).
- know how to write and structure programs of several dozens of lines of code, including scripts and functions.
- be able to read commonly used data formats in atmospheric sciences (csv, NetCDF), process the data for simple analyses (averages, quality filter), and plot the results of your analyses.
- have a basic knowledge of formal code testing (pytest, asserts).
- know how to install a programming environment with appropriate additional packages on your own computer, and use it to solve common programming tasks of the atmospheric sciences. 

Most importantly: **you will be able to expand and deepen your programming skills independently**!

## Prerequisites

The targeted audience for this lecture are **students at the bachelor level without previous experience in programming**. A background in atmospheric sciences (introduction lecture) is desireable, with some knowledge of math and physics, and interest for scientific analysis and number crunching!

## Organisation of the class

The class is taught in English. But it is okay to ask questions in German!

This class follows the [flipped classroom](https://en.wikipedia.org/wiki/Flipped_classroom) model. You will acquire new knowledge at home by reading online materials (and watching videos when appropriate). This will allow to use the time together in class more efficiently to discuss the materials and write code.

<br>

The semester is 15 weeks long. **Each week will always be organised as such**:

- **On Tuesdays (08h15-10h00):** We begin the lecture with a short, individual online assessment to check if you understood the materials that you will have reviewed at home correctly. Based on your own assessment, you choose the topics and questions you would like to discuss in class. I can  delve deeper into specific topics, or present small exercises to help reinforce the key concepts. At the end, you’ll receive instructions on the materials to read or watch for the following week.
- **On Wednesdays (08h15-09h00):** We meet to discuss the assignment solutions (assignments are mandatory but not graded, see "Grading" below). At the end of the class, you’ll receive instructions for the next homework assignment.
- **New week: start again!**

```{important}
The class grants you 5 ECTS if successfully passed: in theory, this represents 8 to 10 hours work per week (not including holidays). For this course, it means that you will spend at least twice as much time doing homework than sitting in class.

I strongly recommend to work regularly for the class. Programming is quite different to other disciplines, and "doing nothing for a few months" cannot be replaced by a "no-sleep-48-hours-push" at the end of semester. Programming is a bit like learning how to ski or climb: it is best learned by doing, and you will notice that regular practice will make you better each week.
```

## Grading 

The lecture will be graded based on four elements:
1. **participation to the weekly assignments** (mandatory but not graded)
1. **mid-term exam: 10%** (Tue 2025-05-06)
2. **a programming project at the end of the semester: 30%** (in group)
3. **final exam at the end of the semester: 60%** (Tue 2025-06-24)

A positive evaluation of each of these elements is mandatory to pass the class!

**Weekly assignments**

Each Wednesday, we will discuss the weekly assignment solutions together. Before the class, each student will have to upload their solution to OLAT (deadline 08h00). I will then select one or two solutions (at random) as a basis for the class discussion. This assignment is **not** graded, and it's okay (or even expected!) to make mistakes. However, it is mandatory to upload your solution each week (you have two "jokers" that you may use at your wish during the semester). The mandatory exercises start at week 02.

**Programming project**

At the end of the semester, you will be given a programming project to realize over two weeks. Ideally, it will be a project that raises your interest: plotting climate or (live) weather data, etc. The grading will be explained once the project starts.

**Mid-term exam**

The mid-term exam (~45', OLAT-exam with presence in class) will take place on **Tue 2025-05-06 at 08:15**.

**Exam**

The final exam (~90', OLAT-exam with presence in class) will take place on **Tue 2025-06-24 at 08:15**.


## Weekly lesson plan 

The first half of the class will be heavily based on the "[Python for Everybody (PY4E)](https://www.py4e.com)" online textbook, which will teach us most of the fundamentals. Towards the second half of the semester, we will shift our focus towards **scientific python**, which can be seen as a special "branch" of the language.

- Week 01 (04.03.25 - 10.03.25)
    - Welcome! Motivation & syllabus
    - [Installing Python](week_01/01-Installation)
    - [PY4E: Why program](https://www.py4e.com/lessons/intro)
- Week 02 (11.03.25 - 17.03.25)
    - [PY4E: Variables, expressions and statements](https://www.py4e.com/lessons/memory)
    - [PY4E: Conditional Execution](https://www.py4e.com/lessons/logic)
    - [Using Jupyter](week_02/02-Intro-jupyter)
- Week 03 (18.03.25 - 24.03.25)
    - [Using Jupyter Notebooks](week_03/01-Intro-notebooks)
    - [PY4E: Functions](https://www.py4e.com/lessons/functions)
    - [PY4E: Loops and Iterations](https://www.py4e.com/lessons/loops)
- Week 04 (25.03.25 - 31.03.25)
    - [Python functions and doctests](week_04/01-documenting-functions)
    - [PY4E: Strings](https://www.py4e.com/lessons/strings)
    - [PY4E: Files](https://www.py4e.com/lessons/files)
    - [PY4E: Lists](https://www.py4e.com/lessons/lists)
- Week 05 (01.04.25 - 07.04.25)
    - [Installing Packages](week_05/01-install-packages)
    - [More on jupyter notebooks](week_05/02-jupyter-dos)
    - [Introduction to numpy and matplotlib](week_05/03-numpy)
- Week 06 (08.04.25 - 11.04.25)
    - [Python tuples](week_06/01-tuples)
    - [numpy - continued: computations](week_06/02-computations)

**Easter break and out-of-office for a conference (14.04.2025 - 04.05.2025)** 

**Mid-term-exam (06.05.2025)**

- Week 07 (13.05.25 - 19.05.25)
    - [numpy - continued: numerics](week_07/01-numerics)
- Week 08 (20.05.25 - 26.05.25)
    - [python dictionaries](week_08/01-dictionaries)
    - [Pandas - manipulating tabular data](week_08/02-pandas)

**Start projects: 26.05.2023. Submission deadline: 06.06.2023.**
    
- Week 09 (03.06.25 - 09.06.25)
    - [numpy - continued: multi dimensional arrays](week_09/01-multidim-numpy)
- Week 10 (10.06.25 - 16.06.23)
    - [Scientific python](week_10/01-scientific-python)
    - [Recipes](cookbook/intro)
    
**Final exam: 24.06.2025**

You will notice that there are 10 weekly units for a 15 weeks long semester: this is expected since some weeks contain holidays or I am traveling. Furthermore, some weeks will be kept free to work on your projects or learn for the exams.
