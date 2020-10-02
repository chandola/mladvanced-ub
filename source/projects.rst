Project Ideas
=============
Here are a few ideas for the course project (to be done in groups of 3). These are very high-level suggestions, and you will have to "fill in the gaps". Feel free to discuss possible directions with the instructor.

.. note:: If you are currently working on a research project, as part of a different course or towards your MS/PhD thesis, and you would like to use that for the course project, please discuss with the instructor. This will be allowed, as long as a clear project plan is presented along with a discussion on how the course project will be different from the original research project.

***********************************************
Optimal model selection with Gaussian processes
***********************************************
Choose a problem that you like (connected to your research, or some publicly available data set) and apply GP learning to it. You can choose a regression, classification, or a dimensionality reduction problem. Determine the optimal kernel for the task. How will you model any structural relationships (temporal, spatial, network-based) in the data?

**************************
Scaling Gaussian Processes
**************************
One of the key challenges with GP learning is the computational complexity. In this course, we will discuss several strategies to the alleviate that issue. Choose a *big* problem and apply different scaling strategies. What impact does each have on the computational complexity and the accuracy of the model.

**********************************************
Bayesian optimization using Gaussian Processes
**********************************************
`Bayesian optimization <https://arxiv.org/abs/1807.02811>`_ is an optimization strategy that can be used when one cannot calculate the gradient of a function, and it has some strong applications in hyper-parameter tuning for machine learning algorithms, including `deep neural networks <https://papers.nips.cc/paper/7472-neural-architecture-search-with-bayesian-optimisation-and-optimal-transport.pdf>`_. Central to Bayesian optimization is the use of GP to approximate the objective function. Demonstrate the use of GP for Bayesian optimization, using a real-world problem and a machine learning algorithm, on the task of identifying the best hyper-parameters.

********************************************
Deep learning methods and Gaussian Processes
********************************************
There are `connections <https://arxiv.org/abs/1711.00165>`_ between deep learning and GPs. However, here the task to understand the benefits and shortcomings of each method in solving a real-world problem. What can you get from GP that you cannot get from neural networks? Think predictive uncertainty and input uncertainty. Can the two be combined?

Computing Resources
===================
All students will access to a GPU-enabled node. To access the resource do the following:

1. Go to the following link from your browser::

       https://rdweb.wvd.microsoft.com/webclient/index.html
2. Use your `<UBIT ID>@buffalo.edu` email address and password to login.

   .. warning:: You will have to go through the DUO two-factor authentication process to login.
3. Choose either `Jupyter Lab` or `Jupyter Notebook` resource from the following page. You will be asked to authenticate again using your UB email and password.
4. You can now create new notebooks and utilize the resource.  

   .. note:: While the Python environment has several relevant libraries, such as ``numpy``, ``pandas`, ``matplotlib``, ``GPy``, ``scikit-learn``, ``GPFlow``, ``Tensorflow+Keras``, contact me if you need any additional libraries.
5. You can use the **One Drive** resource to upload data files to the environment. The resource is available from your browser by going to::

        https://onedrive.live.com/about/en-us/signin/

6. You will have to go through the same authentication process to get to the drive. You can upload (or download) data here. This folder is accessible in the above cloud environment as the following directory::

        OneDrive - University at Buffalo

*****************
Using TensorFlow
*****************

In order to manage the memory of the virtual node, please include the following after importing ``tensorflow``
::
  import tensorflow as tf
  gpus = tf.config.experimental.list_physical_devices('GPU')

  if gpus:
     # Restrict TensorFlow to only allocate 1GB of memory to the first GPU
     try:
        tf.config.experimental.set_virtual_device_configuration(gpus[0],[tf.config.experimental.VirtualDeviceConfiguration(memory_limit=711)])
        logical_gpus = tf.config.experimental.list_logical_devices('GPU')
        print(len(gpus),"Physical GPUs,",len(logical_gpus),"Logical GPUS")
     except RunTimeError as e:
        # Virtual devices must be set before GPUs have been initialized
        print(e) 
