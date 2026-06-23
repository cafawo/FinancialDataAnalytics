![head.png](figures/head.jpg)

# Financial Data Analytics in Python

**Jun.-Prof. Dr. Fabian Woebbeking**</br>
Assistant Professor of Financial Economics

IWH - Leibniz Institute for Economic Research</br>
MLU - Martin Luther University Halle-Wittenberg

fabian.woebbeking@iwh-halle.de

## Course Description and Learning Experience

This course offers a hands-on introduction to data analytics in financial economics. It combines methods from data science, statistics, and textual analysis, with a focus on tools and concepts that are directly relevant for financial economists.

Teaching is highly interactive and practice-oriented. Concepts are introduced through interactive notebooks, coding, and applied exercises, supported by real-world case studies and light gamification elements. Students learn how to work with financial data using Python, SQL, and modern workflows, and apply these skills to solve economically meaningful problems.

The course emphasizes both understanding and implementation: students are encouraged not only to produce working solutions, but also to understand the economic questions and assumptions behind them.

## Schedule and location

The course schedule and rooms are announced on Stud.IP, see important links below. Lectures start as scheduled **cum tempore ($t + 15$ minutes)!** If you have trouble finding the room, please take a look at this [MAP](https://computerpool.wiwi.uni-halle.de/lageplan_pc-pools/).

## Registration (!)

Every student is welcome to attend the course and submit assignments. However, **you MUST register in Löwenportal as well as personally sign the registration form** in order to receive a grade! The registration form will be available in class **until 2026-04-29**. This requirement is independent of the submission of deliverables (homework and cases), which is explained further below.

## Important links and **deadlines (!)**

* [Course repository](https://github.com/cafawo/FinancialDataAnalytics): Everything you need can be found on or is linked to this page.
* [Stud.IP page](https://studip.uni-halle.de/dispatch.php/course/overview?cid=5341d64c24c39be7fb4a90d4ff291d6c): The schedule and lecture rooms are listed here.
* [Support (Q&A)](https://github.com/cafawo/FinancialDataAnalytics/discussions): Essentially a dynamic FAQ section; you can post questions and see other students’ Q&A here.
* [StudySnips Leaderboard 🏆](https://studysnips.eu.pythonanywhere.com/leaderboard/?classroom=zz6): We employ a small gamification element for honor and bonus points.
* Homework** and case submission:
  * [01_setup](https://classroom.github.com/a/cGZUsHTR) [Due Jun 30, 2026, 08:00 UTC]
  * 02_python [Due May 6, 2026, 08:00 UTC]
  * 03_montecarlo [Due May 13, 2026, 08:00 UTC]
  * 04_var [Due May 27, 2026, 08:00 UTC]
  * 05_optimization [Due May 27, 2026, 08:00 UTC]
  * 06_nlp [Due June 3, 2026, 08:00 UTC]
  * **esg_reporting case presentation [Due July 1, 2026, 08:00 UTC]**
  * 07_datam [Due July 31, 2026, 08:00 UTC]
  * 08_django [Due July 31, 2026, 08:00 UTC]
  * 09_satellites [Due July 31, 2026, 08:00 UTC]
  * 10_django_pt2 [Due July 31, 2026, 08:00 UTC]
  * **esg_reporting case final submission [Due July 31, 2026, 08:00 UTC]**

> ** Please submit all homework assignments to the 01_setup repository. You can find all homework assignments in the corresponding [homework/](https://github.com/cafawo/FinancialDataAnalytics/tree/master/homework) folder.

> *** Three **optional** homework assignments are available, for example if you have missed a previous assignment. The **best seven count** toward your grade.

## Prerequisites

* Strong interest in financial economics
* Basic knowledge of programming (preferably Python) and statistics
* All the software used during this course is open-source and free, this includes:
    * Python**
      * [GitHub Codespaces](https://github.com/features/codespaces), a server based Python environment
      * [Miniforge (conda-forge)](https://conda-forge.org/download/), to run Python locally on your machine (macOS, Windows, Linux) 
      * ... or whatever works for you
    * Git: https://git-scm.com/
    * GitHub: https://skills.github.com/

> ** We will discuss how to get you going during the first lecture. If you already have a working Python setup - great - please carry on. If you're new to Python, you can start by using our Codespaces server, which is even accessible through your tablet.

## Materials

All materials are hosted as a Git repository on GitHub. Slides and homework assignments are provided as [Jupyter Notebooks](https://docs.jupyter.org/en/latest/), which means you can interact directly with everything shown - either on your own computer or on our classroom server.


```bash
FinancialDataAnalytics/
├── cases/  # Case description and supplements
│   └── ...  
├── figures/  # Figures used in slides.ipynb
│   └── ...  
├── homework/  # Homework assignments and solutions
│   └── ...  
├── src/  # Python helper scripts (.py)
│   └── ...  
├── README.md  # Syllabus (this file)
├── slides.ipynb  # Slides
├── slides_pt[n].ipynb  # More slides, see 'structure' below
└── ...  # TBA
```

You can view or download the materials directly from GitHub, using the link above, or you can clone the repository using
```Bash
git clone https://github.com/cafawo/FinancialDataAnalytics.git
```
Make sure to update the repository regularly, especially before a lecture, using
```Bash
git pull
```

## Reading

This course is predominantly hands-on and draws from several subject areas, such as financial economics, data science or textual analysis. As such, there exists no single textbook recommendation. Relevant 'reading' material is linked in the script. That being said, resources include but are not limited to:
* ["Python Data Science Handbook" (Jake VanderPlas)](https://jakevdp.github.io/PythonDataScienceHandbook/)
* ["Python for Finance" (Yves Hilpisch)](https://github.com/yhilpisch/py4fi2nd)
* "Data Analysis for Business, Economics, and Policy" (Gabor Bekes, Gabor Kezdi)
* "Applied Text Analysis with Python" (Benjamin Bengfort, Rebecca Bilbro, Tony Ojeda)
* "The big short" (A. McKay)
* "Margin Call" (J. C. Chandor)
* https://stackoverflow.com/
* https://docs.python.org/3/tutorial/index.html
* https://git-scm.com/book/en/v2

## Grading Policy

The grading policy is discussed in detail during the first lecture.

* Homework assignments: 30%
* Case study: 40%
* Presentation: 30%
* Bonus points: + 10%**
  * StudySnips: https://studysnips.eu.pythonanywhere.com/
  * Quality answers in GitHub discussions: https://github.com/cafawo/FinancialDataAnalytics/discussions
  * Bug bounty (pull requests): https://github.com/cafawo/FinancialDataAnalytics/pulls

> ** Please note that the overall achievable score cannot exceed 100% (1.0).

### How to submit your work

We make heavy use of a system called Git. This serves a dual purpose: first, it allows us to conveniently manage submissions throughout the course; second, it familiarizes you with one of the most important tools used in modern software development and data science. All students are therefore required to register using the classroom link found at the top of this page under “Important links.” This will be discussed in the first lecture.

You can use your existing GitHub account or create a new account free of charge. Please note that you can optionally sign up for GitHub Pro, which is offered free of charge with your university email address.

All deliverables must be submitted through this system. To this end, there is one simple rule:

**stage + commit + push = submit!**

If this doesn’t make much sense to you now, don’t worry. We will discuss how to use Git and GitHub extensively, and you will have tutorial sessions for additional guidance.

### Deadlines

* Homework assignments: deadlines are communicated via GitHub Classroom and listed under “Important links” above.
* Case studies: deadlines are announced with the respective case descriptions.

The deadlines for all deliverables are tracked using commit timestamps (Git); no emails are necessary. We will discuss this in more detail later.

## Use of AI

This course embraces the use of AI systems (e.g. large language models and coding assistants) as productive tools for learning, coding, and data analysis. When used responsibly, AI can substantially improve efficiency, help explore ideas, and support understanding of complex concepts.

Using AI does not replace independent thinking or responsibility for results. Blindly copying AI-generated content without verification is strongly discouraged and may lead to incorrect or misleading outcomes.

Best practices, efficient workflows, and common pitfalls of AI-assisted coding and analysis will be discussed throughout the course.

## Structure

### Part 1: Introduction ([slides_pt1.ipynb](https://github.com/cafawo/FinancialDataAnalytics/blob/master/slides.ipynb))

* Discussion of grading scheme and deliverables
* Setting up the tech
  * Git and GitHub
  * Necessary Python libraries
* Coding with AI (best practices and prompt engineering)
* Introduction to the Python programming language
* Data types and structures
* Packages and modules
* Complex data structures
* Plotting

### Part 2: Stochastic and numerical methods

* Random numbers
* Probability distributions
* Cholesky decomposition
* Numerical integration
* Numerical optimization
* Stochastic processes
* Monte Carlo simulation
* Valuation
* Risk measures

### Part 3: Financial time series
* Correlation
* Linear regression models (OLS)
* Auto regressive models (AR)
* Moving average models (MA)
* Auto regressive moving average (ARMA)
* Cointegration
* Empirical stylized facts

### Part 4: Data management
* Object-oriented programming
* Loose coupling
* Market data APIs
* Structured query language (SQL)
* More on Git (.gitignore)
* Large file storage
* Virtual environments

### Part 5: Data sourcing
* Web scraping
* Server infrastructure
* Scheduled tasks
* Logging

### Part 6: Natural language processing (NLP)
* Processing textual data
* Bag of words
* Word embedding
* Transformer architecture
* Large Language Models (LLM)
* ChatGPT API

### Guest lecture: Agentic AI ([GitHub LINK](https://github.com/dsaad68/agno-workshop))
* Introduction to agentic AI systems
* Overview of Python's Agno framework
* Single-agent and multi-agent systems
* Agent tools and memory
* Model Context Protocol (MCP)

### Case study: TBA

## Disclaimer

This syllabus is a general plan for the course; deviations announced to the class by the instructor may be necessary.
