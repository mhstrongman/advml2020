# SC4/SM8 Advanced Topics in Statistical Machine Learning

* Times: Fridays 1000-1100, 1400-1500, Hilary Term 2020.
* Venue: Large Lecture Theatre LG.01, [Department of Statistics, University of Oxford](http://www.stats.ox.ac.uk/)
* Lecturer: [Yee Whye Teh](http://www.stats.ox.ac.uk/~teh/)
* Website: https://github.com/ywteh/advml2020

Announcements:
* 5/3: [Razvan Pascanu (DeepMind)](https://github.com/ywteh/advml2020/wiki/Guest-Lecture:-Razvan-Pascanu-(DeepMind)) will be giving a guest lecture on optimisation and data-efficiency in deep learning.
* 5/3: [Problem sheet 3](https://github.com/ywteh/advml2020/blob/master/problemsheets/sheet3.pdf) available now, and due 5/3 noon.
* 28/2: Lecture times moved to 2-4pm (back to back).
* 27/2: [Arthur Gretton (Gatsby Unit, UCL)](https://github.com/ywteh/advml2020/wiki/Guest-Lecture:-Arthur-Gretton-(Gatsby-Unit,-UCL)) will be giving a guest lecture on GANs and MMD.
* 20/2: [Problem sheet 2](https://github.com/ywteh/advml2020/blob/master/problemsheets/sheet2.pdf) available now, and due 20/2 noon.
* 13/2: [Nicolas Heess and Leonard Hasenclever (DeepMind)](https://github.com/ywteh/advml2020/wiki/Guest-Lecture:-Nicolas-Heess-and-Leonard-Hasenclever-(DeepMind)) will be giving guest lecture 1-3pm.
* 7/2: Direct link to [lecture recordings](https://ox.cloud.panopto.eu/Panopto/Pages/Sessions/List.aspx#folderID=%22d6d22cc2-a81f-4827-9e02-ab4b009b59d0%22).
* 7/2: Slides for weeks 1-3 and problem sheet 1 answers uploaded. 
* Part C/OMMS: due Thursday noon week 3. MSc: class Friday 3pm week 3.

Links:
* [course information](https://github.com/ywteh/advml2020/blob/master/README.md#course-information)
* [course materials](https://github.com/ywteh/advml2020/blob/master/README.md#course-materials)
* [special guest lectures](https://github.com/ywteh/advml2020/blob/master/README.md#special-guest-lectures)
* [information for students](https://github.com/ywteh/advml2020/blob/master/README.md#information)
  * for [Part C and OMMS students](https://github.com/ywteh/advml2020/blob/master/README.md#information-for-part-c-and-omms-students)
  * for [MSc Statistical Science students](https://github.com/ywteh/advml2020/blob/master/README.md#information-for-msc-statistical-science-students)
  * for [DPhil and CDT students](https://github.com/ywteh/advml2020/blob/master/README.md#information-for-dphil-and-cdt-students)

## Course Information

### Aims and objectives:
Machine learning is widely used across the sciences, engineering and society, to construct methods for identifying interesting patterns and predicting accurately from large datasets.
This course introduces several widely used machine learning frameworks and describes their underpinning statistical principles and properties. The course studies both unsupervised and supervised learning and several advanced and state-of-the-art topics are covered in detail. The course will also cover computational considerations of machine learning algorithms and how they can scale to large datasets.

### Prerequisites:
_A8 Probability_ and _A9 Statistics_.  
Some material from this year's syllabus of _SB2.2 Statistical Machine Learning_, PCA and the basics of clustering, will be used (which is mainly taught in the first three lectures of SB2.2, also in HT2019), but SB2.2 is not a prerequisite and background notes will be provided.

### Synopsis:
* Review of unsupervised and supervised learning.  
* Duality in convex optimization and support vector machines.  
* Kernel methods and reproducing kernel Hilbert spaces. Representer theorem. Representation of probabilities in RKHS.  
Kernel PCA. 
* Deep learning. Representation learning. Neural networks and computation graphs. Automatic differentiation. Stochastic gradient descent.
* Probabilistic machine learning: latent variable models, EM algorithm, mixtures, mixtures of experts, probabilistic PCA.
* Variational inference, deep generative models, variational auto-encoders.
* Bayesian learning: Laplace Approximation. Variational Bayes, Latent Dirichlet Allocation.  
* Collaborative filtering models, probabilistic matrix factorization.  
* Gaussian processes for regression and classification. Bayesian optimization. 

### Textbooks and Background Reading
#### Recommended textbooks:
+ Bishop, _Pattern Recognition and Machine Learning_, Springer.
+ Murphy, _Machine Learning: A Probabilistic Perspective_, MIT Press.
+ Hastie, Tibshirani and Friedman, _The Elements of Statistical Learning_, Springer. [ebook](http://www-stat.stanford.edu/%7Etibs/ElemStatLearn/)
+ Shalev-Shwartz and Ben-David, _Understanding Machine Learning: From Theory to Algorithms_, Cambridge University Press.
+ Ian Goodfellow, Yoshua Bengio and Aaron Courville, _Deep Learning_, MIT Press. [website](https://www.deeplearningbook.org/)

#### Background Review Aids:
+ [Matrix](http://www.cs.nyu.edu/~roweis/notes/matrixid.pdf) and [Gaussian](http://www.cs.nyu.edu/~roweis/notes/gaussid.pdf) identities - short useful reference for machine learning.
+ [Linear Algebra Review and Reference](http://cs229.stanford.edu/section/cs229-linalg.pdf)- useful selection for machine learning.
+ [Video reviews on Linear Algebra](http://www.cs.cmu.edu/~zkolter/course/linalg/index.html) by Zico Kolter
+ [Video reviews on Multivariate Calculus and SVD](https://www.youtube.com/channel/UC7gOYDYEgXG1yIH_rc2LgOw/playlists) by Aaditya Ramdas
+ [The Matrix Cookbook](http://www2.imm.dtu.dk/pubdb/views/edoc_download.php/3274/pdf/imm3274.pdf) - extensive reference.

### Software

#### R

+ [Installation](http://cran.r-project.org/)
+ [Introduction](a href="http://cran.r-project.org/doc/manuals/R-intro.pdf)

#### Python

+ [Getting started](https://www.python.org/about/gettingstarted/)
+ [Scikit-learn tutorials](http://scikit-learn.org/stable/tutorial/)

#### Jupyter notebooks
+ [website](https://jupyter.org/)

Knowledge of Python is not required for this course, but some descriptive examples in lectures may be done in Python. Students interested in further Python training are referred to the [free University IT online courses](https://help.it.ox.ac.uk/courses/overview).

 


## Special Guest Lectures:
There will be a series of special guest lectures on (even more) advanced topics in machine learning. These will be 1.5-2 hours in length, with first half being more pedagogical introduction to an area and second half a research seminar. These are not examinable.

* Some Thursdays in LG.01
* Feb 13 1300-1500 week 4: Nicolas Heess and Leonard Hasenclever (DeepMind) on reinforcement learning and control
* Feb 27 1330-1500 week 6: [Arthur Gretton (Gatsby Unit, UCL)](https://github.com/ywteh/advml2020/wiki/Guest-Lecture:-Arthur-Gretton-(Gatsby-Unit,-UCL))
* Mar 5 week 7: Razvan Pascanu (DeepMind) on looking at data efficiency from the learning algorithm perspective
* Mar 6 **Friday 330-430pm** week 8: Max Welling (Amsterdam, Qualcomm) (departmental distinguished seminar)
* Mar 12 1300-1500 week 8: Silvia Chiappa (DeepMind)

## Course Materials
The course materials will appear here before the course starts. They consist of notes, slides, and Jupyter notebooks. Notes may not be exhaustive and should be used in conjunction with the slides. All materials may be updated during the course and are thus best read on screen. Please email me any typos or corrections.

### Notes:
* [Notes up to kernels](https://github.com/ywteh/advml2020/blob/master/notes.pdf). Updated 23/1/2020.

### Slides:
* [slides01](https://github.com/ywteh/advml2020/blob/master/slides/slides01.pdf): Admin, PCA, K-means, empirical risk minimisation
* [slides02](https://github.com/ywteh/advml2020/blob/master/slides/slides02.pdf): Convex duality, SVMs, kernels

### Problem Sheets:
* [sheet1](https://github.com/ywteh/advml2020/blob/master/problemsheets/sheet1.pdf) due Thursday noon week 3

### Other Resources:
* [canvas.ox page](https://canvas.ox.ac.uk/courses/18791)
* [stats.ox student resources](http://www.stats.ox.ac.uk/student-resources/bammath/)
* [lecture recordings](https://ox.cloud.panopto.eu/Panopto/Pages/Sessions/List.aspx#folderID=%22d6d22cc2-a81f-4827-9e02-ab4b009b59d0%22)


## Information:

### Information for Part C and OMMS Students
* [weblearn intercollegiate class signup](https://weblearn.ox.ac.uk/portal/site/:mpls:stats:mmathba_math:class-signup)
* [miverva intercollegiate class list](https://minerva.stats.ox.ac.uk/perl/classlists.pl)
* Problem sheets are due Thursday noon weeks 3,5,7,TT1
* Classes are on weeks 4,6,8,TT1
* Class tutors and TAs:
  * [Adam Foster](http://csml.stats.ox.ac.uk/people/foster/)
  * [Emile Mathieu](http://csml.stats.ox.ac.uk/people/mathieu/)
  * [Deborah Sulem](http://www.oxwasp-cdt.ac.uk/2018-student-cohort.html)
  * [Jin Xu](http://csml.stats.ox.ac.uk/people/xu/)
  * [Michael Hutchinson](https://statml.io/index.php/cohort-1/)
  * [Jean-Francois Ton](http://csml.stats.ox.ac.uk/people/ton/)


### Information for MSc Statistical Science Students
* Classes are Fridays 1500-1600 weeks 3,5,8,TT1 in LG.01

### Information for DPhil and CDT students
* Assessment will be via reproducibility challenge projects.
* Aim is to reproduce recent ML conference papers.
* Papers assigned in weeks 7,8.
* 4 page reports, open sourced software repositories, and 20 min presentation due in early TT.

