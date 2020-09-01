.. CSE610 course webpage documentation master file, created by
   sphinx-quickstart on Fri Mar 17 21:28:07 2017.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

Syllabus
====================================================================

`Computer Science and Engineering <http://www.cse.buffalo.edu/>`_, University at Buffalo 

Fall Semester 2020


.. raw:: html

    <style> .red {color:red} </style>
    <style> .blue {color:blue} </style>
    <style> .gr {color:green;font-weight:bold} </style>
    <style> .highlights {background-color:#ef9c7f;padding:1em} </style>

Instructors
------------

* `Varun Chandola <http://www.cse.buffalo.edu/~chandola>`_ (lead instructor; chandola[at]buffalo.edu)

.. note::
   Students are strongly encouraged to use the Piazza's private messaging option to contact the intructors to ensure that the messages are dealt with promptly. 

Meeting times and locations
----------------------------
.. csv-table::
   :file: timings.csv
   :header: "", "Day", "Time", "Location"
   :widths: 8, 15, 12, 10

.. attention:: 
 This class will taught in a **HyFlex Mode**. The class content covered during the in-person lectures will be available online through UB Panopto, both live and recorded. A separate session on zoom will be available during the lectures for asking questions. All office hours will be conducted remotely on zoom.

Prerequisites
---------------
CSE474/574 (Introduction to Machine Learning) or equivalent. A strong background in linear algebra and probability/statistics is expected. 

Programming Requirements
------------------------
All in-class demonstrations and homework-related codes will be in ``Python 3.x``. We will use ``GPy``, a native library for Gaussian Process (See `<https://sheffieldml.github.io/GPy/>`_ for details and installation instructions). Additionally, we will also explore two modern libraries, `GPyTorch <https://gpytorch.ai>`_ and `GPflow <https://github.com/GPflow/GPflow>`_ to develop scalable GP based solutions for large scale problems.

CSE MS Requirements 
---------------
- The final project in this class satisfies the MS project requirement for the CSE Masters program.
- This class will be considered as an AI focus area course, with regards to the CSE graduate requirements.

Topic Schedule
---------------
.. role:: red
.. role:: gr
.. csv-table::
   :file: topics.csv
   :header: "Week", "Topic", "Notebook", "Resources"
   :widths: 9,30,20,20 


Course Deliverables
-------------------

+------------------------+--------------+-----------+
| Deliverable            | Release Date | Due Date  |
+========================+==============+===========+
| Homework 0             | Sep 1        |  Sep 8    |
+------------------------+--------------+-----------+
| Homework 1             | Sep 8        |  Sep 22   |
+------------------------+--------------+-----------+
| Project Description    |              |  Sep 29   |
+------------------------+--------------+-----------+
| Homework 2             | Sep 22       |  Oct 6    |
+------------------------+--------------+-----------+
| Homework 3             | Oct 6        |  Oct 20   |
+------------------------+--------------+-----------+
| Project Status Report  |              |  Oct 27   |
+------------------------+--------------+-----------+
| Homework 4             | Oct 20       |  Nov 3    |
+------------------------+--------------+-----------+
| Homework 5             | Nov 3        |  Nov 17   |
+------------------------+--------------+-----------+
| Homework 6             | Nov 17       |  Dec 8    |
+------------------------+--------------+-----------+
| Project Presentation   |              |  Dec 1,4  |
+------------------------+--------------+-----------+
| Project Final Report   |              |  Dec 15   |
+------------------------+--------------+-----------+

.. note::
  * Homeworks 

    * Will be released every Tuesday at 9.00 AM EST
    * Due in two weeks before the end of the Tuesday lecture
    * Homework 0 will not be evaluated (warm up)
    * All homeworks will be submitted electronically on UBLearns
    * Homeworks will include mathematical derivations, analytical proofs and data analysis 

Term Project
---------------------------------
  * Students will work in groups of 3 on a semester long project.
  * The choice of topic will be flexible but should involve using the models discussed in class.
  * A two-page project description, detailing the plan, expected outcomes, and milestones, will be due (submitted electronically via UBLearns) on September 29.
  * A two-page mid-semester report project description, detailing the plan, expected outcomes, and milestones, will be due (submitted electronically via UBLearns) on September 29.
  * Each group will make a 15 minute project presentation during the last week of classes (Dec 1 and 4) detailing their findings.
  * A 5-10 page final project report, detailing the methodology and findings of the project, will be due at the end of the semester on December 15th.

Course Texts
---------------
* [GPMLBook] Carl Rasmussen and Christopher Williams, `Gaussian Process for Machine Learning <http://gaussianprocess.org/gpml/chapters/>`_, MIT Press, 2006.
* [PONotes] Peter Orbanz, :download:`Lecture Notes on Bayesian Nonparametrics <porbanz_BNP_draft.pdf>`, *unpublished*, 2014.

Grading
---------
* Homeworks (6) -- 60%
* Final Project  -- 40%
* Final grade cut-offs (*TBA*)

Exams
---------------
* This course has no exams 

Expectations
-------------
* Students are expected to act in a professional manner. A student’s grade may be reduced due to unprofessional or disruptive behavior. Examples include coming to class late, texting (or otherwise using your cell phone) during class, your cell phone ringing during class and/or exams, etc.
* Homeworks will be graded and returned to students.
* :red:`Late submission of homeworks will receive a grade of zero.`
* Students are encouraged to discuss homeworks and share ideas, but each student must independently write and submit their own solution.

Accessibility Services and Special Needs
-----------------------------------------
If you have a disability and may require some type of instructional and/or examination accommodation, please inform me early in the semester so that we can coordinate the accommodations you may need. If you have not already done so, please contact the Office of Accessibility Services (formerly the Office of Disability Services) University at Buffalo, 25 Capen Hall, Buffalo, NY 14260-1632; email: stu-accessibility@buffalo.edu Phone: 716-645-2608 (voice); 716-645-2616 (TTY); Fax: 716-645-3116; and on the web at http://www.buffalo.edu/accessibility/. All information and documentation is confidential. The University at Buffalo and the School of Engineering and Applied Sciences are committed to ensuring equal opportunity for persons with special needs to participate in and benefit from all of its programs, services and activities.

Academic Integrity
-------------------
This course will operate with a zero-tolerance policy regarding cheating and other forms of academic dishonesty. Any act of academic dishonesty will subject the student to penalty, including the high probability of failure of the course (i.e., assignment of a grade of “F”). It is expected that you will behave in an honorable and respectful way as you learn and share ideas. Therefore, recycled papers, work submitted to other courses, and major assistance in preparation of assignments without identifying and acknowledging such assistance are not acceptable. All work for this course must be original for this course. Additionally, you are not allowed to post course homeworks, exams, solutions, etc., on a public forum. Please be familiar with the University and the School policies regarding plagiarism. Read the Academic Integrity Policy and Procedure for more information: http://undergrad-catalog.buffalo.edu/policies/course/integrity.shtml. Visit the Senior Vice Provost for Academic Affairs web page for the latest information at http://vpue.buffalo.edu/policies/

.. highlights:: 

   **Machine Learning Honor Code**
  
   Against the ML honor code to:

   1. Submit someone else’s work, including from the internet, as one’s own for any submission
   2. Misuse Piazza forum

   You are allowed to:

   1. Have discussions about homeworks. Every student should submit own homework with names of students in the discussion group explicitly mentioned.
   2. Collaborate in a group of 3 for the final project. One submission is required for each group.

.. warning:: 
   * Violation of ML honor code and departmental policy will result in an automatic F for the concerned submission
   * Two violations ⇒ fail grade in the course
