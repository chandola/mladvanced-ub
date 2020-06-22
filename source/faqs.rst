.. _faq:

Frequently Asked Questions
==========

Logistics
---------

Where is the course website?
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

       The course website is `here <index.html>`_. The website has links to the resources for the course.

Where is the course syllabus?
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

       Syllabus is `here <syllabus.html>`_.

When does the course begin?
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

       First class is on January 27th, 2019 (Monday) in Knox 20.
            
What are the other resources I should be aware of?
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

       The course website has links to all the resources that we will be using during the course. We will be using **Piazza** for all communications and announcements and **Gradiance** for the weekly quizzes. The `UBLearns <https://ublearns.blackboard.com/webapps/blackboard/execute/modulepage/view?course_id=_168080_1&cmp_tab_id=_188967_1&editMode=true&mode=cpview>`_ system will be used to manage assignment submissions and grades. The slides and handouts (for printing) are available `here <docs.html>`_. We have also prepared a `glossary <glossary.html>`_ of terms that you can refer to.

       We will be using **Python** as the primary programming language. We will use Jupyter Notebooks for in-class demonstrations. The notebooks are available `here <https://nbviewer.jupyter.org/github/ubdsgroup/ubmlcourse/tree/master/notebooks/>`_. You can also check out the notebooks to your personal computers from `Github <https://github.com/ubdsgroup/ubmlcourse/tree/master/notebooks>`_.

What do I need to do before class starts?
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

       * Sign-up for `Piazza <https://piazza.com>`_ (if you do not have an account aready) and enroll into the `CSE 474/574 class <https://piazza.com/class/jqo5zrstnwu67k>`_.
       * Confirm that the class shows up in your `UBLearns account <https://ublearns.buffalo.edu>`_.
       * Create an account on `Gradiance <http://www.newgradiance.com/services/servlet/COTC?Command=ShowCreateAccountForm>`_.

       .. note:: 
          Make sure that you use your UBIT name as the user id. Gradiance requires the user name to be at least 6 characters. If your UBIT name has less than 6 characters, pad it with the required number of x's to make it 6 character long. For example, if your UBIT name is **jliu**, your Gradiance username should be **jliuxx**. Please use lower-case username only

          Improper usernames could result in incorrect assignment of grades.
       
       * Add the CSE 474/574 class on Gradiance using this token **BA9DA0EA**. Will be available on Jan 27th at 9.00 AM.
          
How do I contact the instructors?
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

       Best way is through Piazza. You may send a private or a public message, depending on the nature of the query. Direct email to instructors might not get handled in time.

              
Content
-------
What will I learn in this course?
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
            
       This course is aimed at providing an introduction to the field of Machine Learning. We will focus on understanding the breadth of topics within this field. ML is a broad field and due to the limited time, we will not be able to explore the topics to great depths. However, we will also go deep into some core concepts that are relevant to a many sub-topics within ML. We will explore three ML tasks, viz., supervised, unsupervised and reinforcement (*new*) learning. At the same time, we will also explore cross-cutting issues such as ethics and fairness associated with ML algorithms.


What will I not learn in this course?
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

       Due to the limited time, we will not be able to cover many ML algorithms that you might have heard of, e.g., decision trees, convolutional neural networks (though we will look at simpler neural networks). At the same time, this course is not about teaching how to use a certain library or a tool. You will learn how to build such tools from scratch.

How important is Math in this course?
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

       Very important. In fact, this course is one of the most math intensive course in the undergraduate CSE program. By the second class (Wednesday), we will be deriving a solution for the minimization of an objective function of a vector variable. Similarily, I will assume a strong background in Probability and Statistics.

What linear algebra topics do I need to know before the class starts?
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

      Some of these topics will be covered in-class and during the recitation sections, but it would be good to brush up on these before the class starts. Also, refer to `glossary <glossary.html>`_ for the notation that we will follow in the class:

      * Matrix-vector product, matrix-matrix product, vector-vector dot product, vector-vector cross product
      * Special matrices: Identity, diagonal, symmetric, matrix transpose
      * Matrix operations: trace, norms (of vectors and matrices), linear independence and rank of a matrix, orthogonal matrices, matrix determinant, quadratic form, eigendecomposition of a matrix
      * Matrix calculus: Gradient of a function, Hessian, Gradients and Hessians of a quadratic function

Attendance
----------

Is in-class attendance mandatory?
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

      While the class videos will be posted (almost) immediately after the class, I would strongly recommend against relying on the videos to understand the material.

Will class videos be posted?
~~~~~~~~~~~~~~~~~~~~~~~~~~~~

      Yes, they will be available within the class `UBLearns <https://ublearns.blackboard.com/webapps/blackboard/execute/modulepage/view?course_id=_168080_1&cmp_tab_id=_188967_1&editMode=true&mode=cpview>`_ website. Look out for a **Panopto Recordings** link on that page. Videos are typically available within 2 hours of the class.


Gradiance
---------
What is Gradiance?
~~~~~~~~~~~~~~~~~~
      Gradiance is an online quiz taking system. We will be using that to administer weekly quizzes. Check the syllabus for the exact schedule.
            
How do I enroll?
~~~~~~~~~~~~~~~~
      * Sign-up `here <http://www.newgradiance.com/services/servlet/COTC>`_. 

      .. warning:: 
         Make sure you use your UBIT name as your username. Any other accounts will be deleted!
      * After creating your account, add the class using token **BA9DA0EA**.

How does it work?
~~~~~~~~~~~~~~~~~
           * Every week one quiz will be available on Wednesday morning at 9.00 AM and will be due the next Tuesday at 11.59 PM.
           * Each quiz will contain 4-5 problems on topics covered the previous week.
           * Each problem will have multiple choices, with only one correct answer.
           * At the end of a submission, the system will give you hints for problems that you answer incorrectly.
           * There will be a 5 minute between successive tries.
           * Maximum 3 tries are allowed.
           * Every wrong answer will result in one negative point.
           * A practice quiz will be posted in the first week.

Piazza
------

What do I need Piazza for?
~~~~~~~~~~~~~~~~~~~~~~~~~~
       We will use Piazza as our primary medium of communication. Students with questions can post on Piazza (either private or public). Additionally, it will be used as a discussion forum to have discussions among students and instructors regarding various course aspects.
            
Why should I be active on Piazza?
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
      It is well-documented that student led discussions on Piazza result in much better learning outcomes compared to a single-direction discourse.

      .. note::
         The top contributor (questions or answers) on Piazza will get "recognized".


Assignments
-----------

What will the assignments entail
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
      The course consists of three programming assignments. Assignments will be done in groups of 3. 

What programming language will be used?
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
      We will be using **Python** as the programming language for the assignments. We will be using the Python 3.x version. Note that if you are using Python 2.x, you might run into issues.
                      
What if I do not know Python?
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
      We will have a couple of recitation sessions to introduce you to Python. However, I will strongly advise you to checkout resources on the web to get started on learning Python, something that will help you in future too.

              * `Installing python, ipython <http://ipython.org/install.html>`_
              * `Python IDE - Canopy <https://store.enthought.com/downloads>`_
              * `More about ipython notebooks <http://ipython.org/notebook.html>`_
              * `Python for Developers, a complete book on Python programming by Ricardo Duarte <http://ricardoduarte.github.io/python-for-developers/>`_
              * `CodeAmerica - Python <http://www.codecademy.com/en/tracks/python>`_
              * `An introduction to machine learning with Python and scikit-learn (repo and overview) by Hannes Schulz and Andreas Mueller <http://nbviewer.ipython.org/github/temporaer/tutorial_ml_gkbionics/blob/master/2\%20-\%20KMeans.ipynb>`_

Are there any computing resources available?
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
      While the programming assignments can be completed on a reasonably modern laptop or desktop, you can utilize the CSE resources (See `here <https://wiki.cse.buffalo.edu/services/content/student-servers>`_ for more information).
