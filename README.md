Download Link: https://assignmentchef.com/product/solved-cs433-project-2
<br>
In this project, you will learn to use the concepts we have seen in the lectures and practiced in the labs on a real-world dataset, start to finish. You will be doing exploratory data analysis to understand your dataset and your features, do feature processing and engineering to clean your dataset and extract more meaningful information, implement and use machine learning methods on real data, analyze your model and generate predictions using those methods and report your findings.

Grading. Project 2 counts 30% to your final grade in the course. We offer you three interesting directions of doing this main project.

<h1>Logistics</h1>

Group formation. For Project 2, you again form a team of 3 members on your own. It can be different from your group in Project 1. If you are still searching for teammates, please use the discussion forum on Moodle. In exceptional cases, if you didn’t manage to form a team of 3 by Dec 1st, contact us.

Submission deadline.          Dec 19th, 2019 (midnight 23:59.59)

<h1>Option A – Machine Learning for Science</h1>

Pick a real-world challenge offered by any research group of the (extended) EPFL campus, subject to availability. You learn about an interesting application domain, and collaborate with the lab to apply machine learning methods to their specific research question, on real data provided by the lab – an exciting option to follow an interdisciplinary approach to find new insights with your team.

Deliverables at a glance.            (More details and grading criteria further down)

<ul>

 <li>Written Report. You will write a maximum 4 page PDF report on your findings, using LaTeX.</li>

 <li>In Python. External libraries are allowed, if properly cited.</li>

</ul>

The guidelines for the projects are the same as in the standard tasks explained below.

Participation of the Hosting Lab. The only major difference to the other options is that here, you do this project in collaboration with another lab on EPFL campus. The lab hosting you will help us grading the domainspecific merit of your contribution. We encourage you to reach out to any lab of your choice at EPFL, UniL, CERN, CHUV, Idiap etc., and ask them for a project idea, or propose an idea to them.

Here is a list of labs which already have proposed several exciting project ideas. Note that other labs are possible as well.

<a href="https://docs.google.com/spreadsheets/d/1Mav7vND2dYghHQxLEXqnvLZ1z9GKRcNynOAjwcQpMPo/">https://docs.google.com/spreadsheets/d/1Mav7vND2dYghHQxLEXqnvLZ1z9GKRcNynOAjwcQpMPo/ </a>Important Logistics: You can only sign up for this option if the <em>professor </em>of that lab agrees to host your group of 3 students, and will confirm this by filling the mandatory registration form for labs, by November 12:

<a href="https://goo.gl/forms/0ElZtbKGz4U0lCag1">https://goo.gl/forms/0ElZtbKGz4U0lCag1</a>

Submission URL for the final project: <a href="http://mlcourse.epfl.ch/">http://mlcourse.epfl.ch</a> (same as for option B)

<h1>Option B – One of our Pre-defined Challenges</h1>

Deliverables at a glance.            (More details and grading criteria further down)

<ul>

 <li>Written Report. You will write a maximum 4 page PDF report on your findings, using LaTeX.</li>

 <li>In Python. External libraries are allowed, if properly cited.</li>

 <li>Competitive Part. To give you immediate feedback and a fair ranking, we use the competition platform AIcrowd.com to score your predictions. You can submit whenever and almost as many times as you like, up until the final submission deadline.</li>

</ul>

Pick Your Favorite Among Three Challenges. Pick your favorite competition among the following three online competitions. Don’t be influenced by their seemingly different difficulty level, since your contribution as compared to standard approaches will be taken into account in the grading.

<h2>Step 1 – Getting started</h2>

In order to be able to access the challenges, please first create an account at AIcrowd.com using your @epfl.ch email address. Pick your favorite competition among the following three. To read the description and download the dataset, please follow the corresponding links:

<a href="https://www.aicrowd.com/challenges/epfl-ml-text-classification-2019">https://www.aicrowd.com/challenges/epfl-ml-text-classification-2019 </a><a href="https://www.aicrowd.com/challenges/epfl-ml-road-segmentation-2019">https://www.aicrowd.com/challenges/epfl-ml-road-segmentation-2019 </a><a href="https://www.aicrowd.com/challenges/epfl-ml-recommender-system-2019">https://www.aicrowd.com/challenges/epfl-ml-recommender-system-2019</a>

For all three possible tasks, we provide some additional description and sample code on the course github:

<a href="https://github.com/epfml/ML_course/tree/master/projects/project2">https://github.com/epfml/ML_course/tree/master/projects/project2</a>

<h2>Step 2 – Implement ML Methods</h2>

You are allowed to use any external library and ML techniques, as long as you properly cite any external code used.

<h2>Step 3 – Submitting your Predictions</h2>

Once you have a working model (using the above methods or a modified one), you can send your predictions to the AIcrowd competition to see how your model is doing against the other teams. You can submit whenever and as many times as you like, until the deadline.

Your predictions must be in .csv format, see sample-submission.csv. You must use the same datapoint ids as in the test set test.csv. To generate .csv output from Python, use our provided helper functions in helpers.py (see Project 1 folder on github).

After a submission, AIcrowd will compute your score on the test set, and will show you your score and ranking in the leaderboard.

Do not use the AIcrowd score as the only estimate of your error. Instead, always estimate your test error by using a local validation set, or local cross-validation! This is important to avoid overfitting the test set online. Also, it allows you to make experiments faster, and save uploading bandwidth :). You are only allowed a maximum of 5 submissions per person to AIcrowd per day.

<h2>Step 4 – Final Submission of Your Project</h2>

Your final submission to the online system (a standard system as used for scientific conferences) must consist of the following:

<ul>

 <li>Report: Your 4 page report as .pdf</li>

 <li>Code: The complete executable and documented Python code, as one .zip file. Rules for the code part:

  <ul>

   <li><em>Reproducibility: </em>In your submission, you must provide a script run.py which produces <em>exactly </em>the same .csv predictions which you used in your best submission to the competition on AIcrowd. This includes a clear ReadMe file explaining how to reproduce your setup, including precise training, prediction and installation instructions if additional libraries are used – the same way as if you would ideally instruct a new teammate to start working with your code.</li>

   <li><em>Documentation: </em>Your ML system must be clearly described in your PDF report and also welldocumented in the code itself. A clear ReadMe file must be provided. The documentation must also include all data preparation, feature generation as well as cross-validation steps that you have used.</li>

   <li><em>External ML libraries </em>are allowed, as long as accurately cited and documented.</li>

   <li><em>External datasets </em>are allowed, as long as accurately cited and documented.</li>

  </ul></li>

</ul>

Submission URL: <a href="http://mlcourse.epfl.ch/">http://mlcourse.epfl.ch</a>

Don’t forget to provide all author names with their EPFL email, as well as the (correct one and only one!) ranking username appearing AIcrowd, and select the right one of the 3 tasks. You can update all parts of your submission anytime until the deadline.

<h1>Option C – NeurIPS Reproducibility Challenge</h1>

Your team participates in the NeurIPS Reproducibility Challenge. Here the goal is to select a new submitted NeurIPS paper, and try to reproduce (parts of) its experiments:

<a href="https://reproducibility-challenge.github.io/neurips2019/">https://reproducibility-challenge.github.io/neurips2019/</a>

<h1>Appendix</h1>

<h2>Grading Criteria and Some Advice</h2>

We are aware that not all tasks have the same difficulty (especially there will be larger variance in options A) and C). We will take the difficulty of the question into account when grading, so none of the choices will have any disadvantage for you.

<ul>

 <li>In Python. You are allowed to use external libraries, as long as properly cited, documented and referenced. Similarly as in Project 1, your project submission will be graded by two assistants independently. As some additional advice for the code part,

  <ul>

   <li>Double-check that the archive you submit actually contains everything needed to run your solution. If your project is for option B), check that your code indeed exactly reproduces your best AIcrowd submission (and select the submission on AIcrowd accordingly).</li>

   <li>Make sure any additional installation needed to run your solution is fully described in the accompanying ReadMe file, including version numbers if necessary.</li>

   <li>Try to follow your own instructions to get your code running at least once.</li>

   <li>Try to make your code as readable as possible. Reduce copy-pasted code to a minimum, use helper functions and clearly name your files, functions and variables.</li>

  </ul></li>

 <li>Written Report. You will write a maximum 4 page PDF report on your findings, using LaTeX. We will grade you on the scientific contribution you made, that is on the improvement achieved over the standard baseline methods, as well as the rigorous and fair measuring of the claimed improvements. The criteria are</li>

 <li>Solid comparison baselines supporting your claims</li>

</ul>

Quantify the benefits of your method by providing clear quality measurements of the most important aspects and additions you chose for your model. Start with a very basic baseline, and demonstrate what improvements your contributions yield.

<ul>

 <li>Reproducibility</li>

</ul>

Your classmates should be able to reproduce your results based on your report only. Describe what preprocessing is required, what hyper-parameter values you selected and why, and clearly describe the overall pipeline you used.

<ul>

 <li>Scientific novelty and creativity</li>

</ul>

You will likely be using more than the standard methods we saw in the first half of the course. To communicate that your methods work and that you understand them, you should make sure that your report makes clear the following points.

<ul>

 <li>What <em>specific </em>problem your method is intended to solve.</li>

</ul>

By specific, we do not mean “image classification” but what specific issue with your current model are you trying to improve with this method.

<ul>

 <li>Why is this an important problem? Why are you solving this one instead of something else?</li>

 <li>How is your method helping?</li>

 <li>What are the results of your method? Compare the error before and after.</li>

</ul>

<ul>

 <li>Writeup quality Some advice:

  <ul>

   <li>Try to convey a clear story giving the most relevant aspects of your approach, in a reproducible way. Learning what has not worked can additionally help the reader (and help them better understand <em>why </em>you have made the many choices you did), but focus on what is most relevant for your final solution.</li>

   <li>Before the submission, have an external person proofread your report. It is easy to write a sentence that makes perfect sense to you since you wrote it but is actually hard to parse. Use a spell-checker.</li>

   <li>Plots are great way to share information that might be hard to convey by writing. Make sure that your plots are understandable, have labels for axes, a title, correct axes limits, add a description of what your plot is about and what can be learned from it.</li>

   <li>Competitive Part (only for option B)). The final rank of your team in the (private) leaderboard will be translated linearly to a scale from 4 to 6.</li>

  </ul></li>

</ul>

As usual, your code and report will be automatically checked for plagiarism.

<h2>Guidelines for Machine Learning Projects</h2>

Now that you have implemented few basic methods, you should use this toolbox on the dataset. Here are a few things that you might want to try.

Exploratory data analysis You should learn about your dataset – figure out which features are continuous, which ones are categorical, check if there are obvious relationships between the features, take a look at the distribution of each feature, and so on. Check <a href="https://en.wikipedia.org/wiki/Exploratory_data_analysis">https://en.wikipedia.org/wiki/Exploratory_data_analysis</a><a href="https://en.wikipedia.org/wiki/Exploratory_data_analysis">.</a>

Feature processing Cleaning your dataset by removing useless features and values, combining others, finding better representations of the features to feed your model, scaling the features, and so on. Check this article on feature engineering: <a href="http://machinelearningmastery.com/discover-feature-engineering-how-to-engineer-features-and-how-to-get-good-at-it/">http://machinelearningmastery.com/discover-feature-engineering-how-to</a><a href="http://machinelearningmastery.com/discover-feature-engineering-how-to-engineer-features-and-how-to-get-good-at-it/">engineer-features-and-how-to-get-good-at-it/</a><a href="http://machinelearningmastery.com/discover-feature-engineering-how-to-engineer-features-and-how-to-get-good-at-it/">.</a>

Determining whether a method overfits or underfits You should be able to diagnose the whether your model is over- or underfitting the data and take actions to fix the problems with your model. Recommended reading: <em>Advice on applying machine learning methods </em>by Andrew Ng: <a href="http://cs229.stanford.edu/materials/ML-advice.pdf">http://cs229.stanford.edu/materials/ML</a><a href="http://cs229.stanford.edu/materials/ML-advice.pdf">advice.pdf</a><a href="http://cs229.stanford.edu/materials/ML-advice.pdf">.</a>

Applying methods and visualizing Beyond simply applying the models we have seen, it helps to try to understand what the ML model is doing. Try to find out which datapoints are wrongly classified and, if possible, why this is the case. Then use this information to improve your model. Check Peter Domingo’s <em>Useful things to know about machine learning</em>: <a href="https://homes.cs.washington.edu/~pedrod/papers/cacm12.pdf">http://homes.cs.washington.edu/</a><a href="https://homes.cs.washington.edu/~pedrod/papers/cacm12.pdf">~</a><a href="https://homes.cs.washington.edu/~pedrod/papers/cacm12.pdf">pedrod/papers/cacm12.pdf</a>

Accurately estimate how well your method is doing    By applying cross-validation and estimating the test error.

<h2>Report Guidelines</h2>

In addition to finding a good model for the data, you will need to explain your methodology in a report.

Clearly describe your used methods, state your conclusions and argue that the results you obtained make (or do not make) sense, and the reasons behind it. Keep the report short and to the point, with a strict limit of 4 pages. References are allowed to be put on a extra page.

To get started more easily with writing the report, we provide you a LaTeX template here

<a href="https://github.com/epfml/ML_course/tree/master/projects/project1/latex-example-paper">github.com/epfml/ML</a> <a href="https://github.com/epfml/ML_course/tree/master/projects/project1/latex-example-paper">course/tree/master/projects/project1/latex-example-paper</a>

The file also contains some more helpful information on how to write a scientific report or paper. We will also help you learn it during the exercise session and office hours if you ask us.

For more guidelines on what makes a good report, see the grading criteria above. In particular, don’t forget to take care about

<ul>

 <li><em>Reproducibility: </em>Not only in the code, but also in the report, do include complete details about each algorithm you tried, e.g. what lambda values you used for ridge regression? How exactly did you do that feature transformation? how many folds did you use for cross-validation? etc…</li>

 <li><em>Baselines: </em>Give clear experimental evidence: When you added this new combined feature, or changed the regularization, by how much did that increase or decrease the test error? It is crucial to always report such obtained differences in the evaluation metrics, and to include several properly implemented baseline algorithms as a comparison to your approach.</li>

</ul>

Some additional resources on LaTeX:

<ul>

 <li><a href="https://github.com/VoLuong/Begin-Latex-in-minutes">https://github.com/VoLuong/Begin-Latex-in-minutes</a> – getting started with LaTeX</li>

 <li><a href="http://www.maths.tcd.ie/~dwilkins/LaTeXPrimer/">http://www.maths.tcd.ie/</a><a href="http://www.maths.tcd.ie/~dwilkins/LaTeXPrimer/">~</a><a href="http://www.maths.tcd.ie/~dwilkins/LaTeXPrimer/">dwilkins/LaTeXPrimer/</a> – tutorial on LaTeX</li>

 <li><a href="http://www.stdout.org/~winston/latex/latexsheet-a4.pdf">http://www.stdout.org/</a><a href="http://www.stdout.org/~winston/latex/latexsheet-a4.pdf">~</a><a href="http://www.stdout.org/~winston/latex/latexsheet-a4.pdf">winston/latex/latexsheet-a4.pdf</a> – cheat sheet collecting most of all useful commands in LaTeX</li>

 <li><a href="http://mirror.switch.ch/ftp/mirror/tex/info/first-latex-doc/first-latex-doc.pdf">http://mirror.switch.ch/ftp/mirror/tex/info/first-latex-doc/first-latex-doc.pdf</a> – example how to create a document with Latex</li>

 <li><a href="https://en.wikibooks.org/wiki/LaTeX">http://en.wikibooks.org/wiki/LaTeX</a> – detailed tutorial on LaTeX</li>

</ul>

<h3>Producing figures for LaTeX in Python</h3>

There are some good visualization tools in Python. “matplotlib” is probably the single most used Python package for 2D-graphics. The relevant tutorials are as follow:

<ul>

 <li>Matplotlib tutorial: <a href="http://www.labri.fr/perso/nrougier/teaching/matplotlib/">http://www.labri.fr/perso/nrougier/teaching/matplotlib/</a></li>

 <li>Matplotlib tutorial: <a href="https://sites.google.com/site/scigraphs/tutorial">https://sites.google.com/site/scigraphs/tutorial</a></li>

 <li>Matplotlib Tutorial: <a href="https://jakevdp.github.io/mpl_tutorial/">http://jakevdp.github.io/mpl_tutorial/</a></li>

</ul>

Regarding other useful Python data visualization libraries, please refer to this <a href="https://jakevdp.github.io/mpl_tutorial/">blog</a> for more information.