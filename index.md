---
layout: default
title: Statistical Computing and Introduction to Data Science
---

# **GR5206 / 4206 - Fall 2025**

## **Learning Outcomes**

* Understand basic programming
   * Manipulate data with different structures  
   * Control flow and logic
   * Functions and modular programming
* Explore data via visualization
* Study statistical concepts via simulations
* Automate tasks with programming
* Understand basic optimization

## **Prerequisites**

* An introductory statistics class
   * Basic probability distributions (e.g. Gaussian, binomial distributions and their likelihoods)  
   * Basic hypothesis testing (e.g. t-test)  
   * Summary statistics  
   * Histograms, boxplots, etc
* Multivariate calculus
   * Derivatives and functions
* Matrix operations and inverses of matrices
* You should be at least co-enrolled in a modeling class like regression

## **Textbooks and References**

* **Google!** *(Your best friend for debugging)*
* [Python concept notes](https://leewtai.github.io/courses/stat_computing/lectures/learning_python_intro.html)
* [Python Data Science Handbook](https://jakevdp.github.io/PythonDataScienceHandbook/)
* **Basics only** - [Programming with Python by Software Carpentry](https://swcarpentry.github.io/python-novice-inflammation/)
* [LearningPython.org](https://www.learnpython.org/)
* **Data engineering references** *(not covered in this class)*:  
   * *Designing Data-Intensive Applications* by Martin Kleppmann (available in NYPL)  
   * *System Design Interview - An Insider's Guide* by Alex Xu
   * *Ace the Data Science Interview* by Kevin Huo and Nick Singh
* AI tools like ChatGPT are generally **NOT allowed** unless explicitly allowed for the assignment. You are strongly discouraged from using them for intro courses which this course is. If you cannot resist the temptation though, it is best that you prompt ChatGPT to ask you questions rather than having it provide you with solutions. You are still responsible for the correctness of your work.

## **Course Timeline**

**Note:** *We reserve the right to change the ordering and the content for the course throughout the semester.*

**Prior to the first class, you should do the following (mandatory):**
Install Jupyter Notebook via Anaconda (Recommended for Beginners).

**You should finish the "required readings" prior to the start of each class on a weekly basis (mandatory).**

| Date              | Topic                                                                                                                                                                                                                                                                                                                                                                                                                      | Required Readings - 1                                                                                                                                                                                                                                                                                                                                                                                  | Required Readings - 2                                                                                                                  | Due                                                                                                                                    |
| ---------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | -------------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------- |
| Week of 9/1/2025 | [Introduction + python as a calculator](https://docs.google.com/presentation/d/1hbdEFneIriuFSxtwfH29LvJp1AX_gZ961FtG4msPL7o/edit?usp=sharing)                                                                                                                                                                                                                                                                            | - [Python concepts 1, 2, 3, 4](https://leewtai.github.io/courses/stat_computing/lectures/learning_python_intro.html)<br>- [Software Carpentry - Python Fundamentals + Analyzing Patient Data](https://swcarpentry.github.io/python-novice-inflammation/)<br>- [Python Data Science Handbook Chapter 2: Understanding Data Types in Python to The Basics of Numpy Arrays](https://jakevdp.github.io/PythonDataScienceHandbook/) | - [Python.org Tutorial](https://docs.python.org/3/tutorial/)<br>- [Real Python - Python Basics](https://realpython.com/python-basics/) |                                                                                                                                        |
| Week of 9/8/2025 | Numpy, objects, and subsetting<br>[AB Testing](https://docs.google.com/presentation/d/1lRzWdkLiwV0_3zBNKcDF6VqOu6JGpXSCy4WZNXH69NM/edit#slide=id.p)                                                                                                                                                                                                                                                                          | [Python concepts 5, 6, 8, 10, 11](https://leewtai.github.io/courses/stat_computing/lectures/learning_python_intro.html)                                                                                                                                                                                                                                                                                          | - [NumPy Documentation](https://numpy.org/doc/stable/)<br>- [NumPy Quickstart](https://numpy.org/doc/stable/user/quickstart.html) | [Set up your jupyter notebook environment with the command line](https://leewtai.github.io/setup/conda_and_navigator_setup.html) |
| Week of 9/15/2025 | [For-loop, if/else, working with files, AB testing assignment](https://docs.google.com/presentation/d/115mFspST_Id7c0qk1H4R2UAmUOQAp_nZO96KPQbcRyc/edit?usp=sharing)                                                                                                                                                                                                                                                   | [Python concepts 7, 9, 21, 23](https://leewtai.github.io/courses/stat_computing/lectures/learning_python_intro.html)                                                                                                                                                                                                                                                                                             | - [Python File I/O](https://docs.python.org/3/tutorial/inputoutput.html#reading-and-writing-files)<br>- [Real Python - Python File Handling](https://realpython.com/python-file-handling/) | HW1 Due                                                                                                                                |
| Week of 9/22/2025 | [Pandas, summaries, and visualization<br>Exploratory data analysis](https://docs.google.com/presentation/d/1qpWNoeyzZnxuKsi4O1v4FJDc6m_V177fIRht_kAhySg/edit?usp=sharing)                                                                                                                                                                                                                                                 | [Python concepts 12, 14, 15, 16](https://leewtai.github.io/courses/stat_computing/lectures/learning_python_intro.html)                                                                                                                                                                                                                                                                                           | - [Pandas Documentation](https://pandas.pydata.org/docs/)<br>- [Matplotlib Tutorials](https://matplotlib.org/stable/tutorials/index.html) |                                                                                                                                        |
| Week of 9/29/2025 | [Nested data and data wrangling<br>Basic data engineering](https://docs.google.com/presentation/d/1c_hbkqKo-_kqrwFSeuebhyAjaNsKvaCAZCmI3pkI2xc/edit?usp=sharing)                                                                                                                                                                                                                                                          | [Python concept 24 and all previous chapters](https://leewtai.github.io/courses/stat_computing/lectures/learning_python_intro.html)                                                                                                                                                                                                                                                                              | - [Pandas User Guide - Data Wrangling](https://pandas.pydata.org/docs/user_guide/reshaping.html)<br>- [JSON Handling in Python](https://docs.python.org/3/library/json.html) | HW2 Due                                                                                                                                |
| Week of 10/6/2025 | Regular expression and interacting with APIs                                                                                                                                                                                                                                                                                                                                                                               | [Python concepts 13, 17](https://leewtai.github.io/courses/stat_computing/lectures/learning_python_intro.html)                                                                                                                                                                                                                                                                                                   | - [Python Regular Expressions](https://docs.python.org/3/library/re.html)<br>- [Requests Documentation](https://requests.readthedocs.io/) |                                                                                                                                        |
| Week of 10/13/2025 | Designing data pipelines                                                                                                                                                                                                                                                                                                                                                                                                   | All previous Python concepts                                                                                                                                                                                                                                                                                                                                                                           | - [Apache Airflow Documentation](https://airflow.apache.org/docs/)<br>- [Python Logging](https://docs.python.org/3/library/logging.html) | HW3 Due                                                                                                                                |
| Week of 10/20/2025 | Midterm in the evening!                                                                                                                                                                                                                                                                                                                                                                                                    |                                                                                                                                                                                                                                                                                                                                                                                                        |                                                                                                                                        |                                                                                                                                        |
| Week of 10/27/2025 | [Data use cases, relational data, and SQL](https://docs.google.com/presentation/d/18RuceAE4_9vM4k7ILTNcpoA2UCarpObwNjdonlgEpjQ/edit?usp=sharing)<br>Data quality concepts and data engineering                                                                                                                                                                                                                               | [Python concepts 20](https://leewtai.github.io/courses/stat_computing/lectures/learning_python_intro.html)                                                                                                                                                                                                                                                                                                       | - [SQLite Tutorial](https://www.sqlite.org/docs.html)<br>- [SQLAlchemy Documentation](https://docs.sqlalchemy.org/) |                                                                                                                                        |
| Week of 11/3/2025 | [Modeling data](https://docs.google.com/presentation/d/1StjjdlxBuHEJidpC3D_NczrsBitZaXmuvIven_xs5c4/edit?usp=sharing)<br>"Data science methods"                                                                                                                                                                                                                                                                            | [Python concepts 18](https://leewtai.github.io/courses/stat_computing/lectures/learning_python_intro.html)                                                                                                                                                                                                                                                                                                       | - [Scikit-learn Documentation](https://scikit-learn.org/stable/)<br>- [Statsmodels Documentation](https://www.statsmodels.org/) |                                                                                                                                        |
| Week of 11/10/2025 | [Optimization](https://docs.google.com/presentation/d/1zcG_RxtVZMPP-ZjkovMpZwXvI-GKbifcGzuU8vMjU-E/edit?usp=sharing)<br>Objective functions                                                                                                                                                                                                                                                                                  | [Python concepts 19](https://leewtai.github.io/courses/stat_computing/lectures/learning_python_intro.html)                                                                                                                                                                                                                                                                                                       | - [SciPy Optimization](https://docs.scipy.org/doc/scipy/reference/optimize.html)<br>- [NumPy Linear Algebra](https://numpy.org/doc/stable/reference/routines.linalg.html) | HW4 Due                                                                                                                                |
| Week of 11/17/2025 | [Bootstrap, permutation, and other simulations](https://docs.google.com/presentation/d/1NiOdRHs7eeB94F-eS3lxJvqZGsKUll2LWwjw7bf5mqk/edit?usp=sharing)<br>Model evaluation<br>[Validation](https://docs.google.com/presentation/d/1OO7WHa8oKpOS0HeTQqeKeWK0MqFlg70d9ytTdTZMm0s/edit?usp=sharing) and [what we don't know](https://docs.google.com/presentation/d/1x_RDVUNHKRA_OH53BqoBpp8QLwQ62WZrk7jnzdBsegE/edit?usp=sharing) |                                                                                                                                                                                                                                                                                                                                                                                                        | - [Bootstrap Methods](https://docs.scipy.org/doc/scipy/reference/stats.html)<br>- [Cross-validation in Scikit-learn](https://scikit-learn.org/stable/modules/cross_validation.html) |                                                                                                                                        |
| Week of 11/24/2025 | Thanksgiving NO CLASS                                                                                                                                                                                                                                                                                                                                                                                                      |                                                                                                                                                                                                                                                                                                                                                                                                        |                                                                                                                                        |                                                                                                                                        |
| Week of 12/1/2025 | Big exam                                                                                                                                                                                                                                                                                                                                                                                                                   |                                                                                                                                                                                                                                                                                                                                                                                                        |                                                                                                                                        | HW5 Due on 11/30                                                                                                                       |
| TBD        | Final                                                                                                                                                                                                                                                                                                                                                                                                                      |                                                                                                                                                                                                                                                                                                                                                                                                        |                                                                                                                                        |                                                                                                                                        |

## **Logistics**

### **Teaching Team**

#### **Section 1**
* Instructor: Benjamin Goodwich Ph.D. benjamin.goodrich@columbia.edu  
* Class time: Fridays 10:10am - 12:40pm  
* Location: 417 INTERNATIONAL AFFAIRS BLDG

#### **Section 2**
* Instructor: Haiyuan Wang Ph.D. hw2592@columbia.edu  
* Class time: Thursdays 6:10pm - 8:40pm  
* Location: 501 Schermerhorn

#### **TAs:** 
* Nikira Walter naw2146@columbia.edu  
* Yizi Zhang yz4123@columbia.edu

#### **Office Hours:**

* **Mondays** Nikira 9:45am - 11:45am  
   * Location: Student Lounge on the 6th Floor, School of Arts and Sciences at Columbia University.

* **Tuesdays** Yizi TBD  
   * Location: TBD

* **Thursdays** Prof. Wang 3:50pm - 5:50pm  
   * Location: Room 610, Watson Hall at Columbia University.  
   * Please reserve your slots from the following link: https://calendly.com/hw2592-columbia/one-one-one-10-minute-meeting  
   * (To schedule a longer session, please book multiple consecutive time slots.)

* **Fridays** Prof Goodrich 2:00pm - 5:00pm  
   * Location: Room 608, Watson Hall at Columbia University.  
   * Please reserve your slots from the following link: https://calendar.app.google/8DTmEBK4SpWv7ceq6

### **Grading**

If your final grade is in [93-97), you will earn at least an A, [90-93) will earn at least an A-, [87-90) will earn at least a B+, etc. A grading curves may occur depending on the class performance but I will not curve downwards. I will not give out A+ for this class.

#### **Homeworks (25%)**

* **Late homeworks will receive 0 credit**
* **No make-up homeworks** will be granted even if you registered late to the class

#### **Exams (65%)**

* Midterm (28%)
* Final (37%)

#### **Participation (10%)**

* In class participation
* Online question posting (non-private) and answers are all ways to achieve this
* I will reach out after the midterm if you are at risk of missing some points here
* **No class absences allowed**

#### **Exam Accommodations**

In order to receive disability-related academic accommodations for this course, students must first be registered with their school Disability Services (DS) office. Detailed information is available online for both the Columbia and Barnard registration processes.

Refer to the appropriate website for information regarding deadlines, disability documentation requirements, and drop-in hours(Columbia)/intake session (Barnard).

For this course, students are not required to have testing forms or accommodation letters signed by faculty. However, students must do the following:

· The Instructor section of the form has already been completed and does not need to be signed by the professor.

· The student must complete the Student section of the form and submit the form to Disability Services.

· Master forms are available in the Disability Services office or online: https://health.columbia.edu/services/testing-accommodations

## **Expectations**

* **Take chances!**  
   * Break the code in lecture *(it's how we learn!)*
* Give feedback in office hours or e-mail, don't waste your time if you think a topic is not helpful
* **Participate and ask questions** - this is not easy!  
   * In class: forecast what should be done, compare with what is happening, then summarize the difference  
   * Online: describe what you observe, describe what you expect, communicate clearly  
   * To each other: summarize the conversation to ensure you're listening and think constructively before criticizing
* Academic honesty: https://www.cs.columbia.edu/education/honesty/

## **Acknowledgement**

A lot of these materials are based off the materials from Prof Thibault Vatter, Prof Gabriel Young, Prof Wayne Lee, and Prof Yongchan Kwon.

---
*Published using **GitHub Pages***