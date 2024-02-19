# Awesome Causality

[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)
[![License: CC0 1.0 Universal (CC0 1.0) Public Domain Dedication](https://licensebuttons.net/l/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

Resources related to causality.
This awesome list is different from other lists as it tries to compile major resources related to causality in one place under different categories.

**NOTE:** This awesome list is still new and under development. Please feel free to contribute, before it can become worth sharing.

- [Awesome Causality](#awesome-causality)
  * [Other Awesome lists](#other-awesome-lists)
- [Data](#data)
- [Tools](#tools)
- [Learning resources](#learning-resources)
  * [Tutorials](#tutorials)
  * [Blogs](#blogs)
  * [Books](#books)
  * [Courses](#courses)
  * [Videos](#videos)
- [Events](#events)
  * [Workshops](#workshops)
- [Communities, and Mailing lists](#communities--and-mailing-lists)
- [Miscellaneous](#miscellaneous)

<small><i><a href='http://ecotrust-canada.github.io/markdown-toc/'>Table of contents generated with markdown-toc</a></i></small>

## Other Awesome lists
These list contain a more focused compilation of algorithms and data related to causality under more specific categories.

* [awesome-causality-algorithms](https://github.com/rguo12/awesome-causality-algorithms)
* [awesome-causality-data](https://github.com/rguo12/awesome-causality-data)

# Data
* [Amazon Review Sales](https://github.com/rguo12/CIKM18-LCVA) - [Google drive](https://drive.google.com/drive/u/1/folders/1Ff_GdfjhrDFbZiRW0z81lGJW-cUrYmo1) - [Paper](https://arxiv.org/abs/1808.03333)
* [Jobs Training](http://users.nber.org/~rdehejia/data/nswdata2.html) - [Train](http://www.fredjo.com/files/jobs_DW_bin.train.npz) [Test](http://www.fredjo.com/files/jobs_DW_bin.test.npz) - [Paper](http://proceedings.mlr.press/v70/shalit17a.html)
* [Twins](https://github.com/AMLab-Amsterdam/CEVAE/tree/master/datasets/TWINS)
* [Synthetic IHDP](https://github.com/AMLab-Amsterdam/CEVAE/tree/master/datasets/IHDP)
* [2016 Atlantic Causal Inference competition](https://github.com/vdorie/aciccomp/tree/master/2016)
* [News trearment effect measurement](http://www.fredjo.com/files/NEWS_csv.zip)
* [Cause effect pairs](http://webdav.tuebingen.mpg.de/cause-effect/)
* [Movie recommendations - Missing not at random (MNAR)](http://www.cs.cornell.edu/~schnabts/mnar/index.html) - [Paper](http://proceedings.mlr.press/v48/schnabel16.html)
* [CHALEARN Fast Causation Coefficient Challenge](http://www.causality.inf.ethz.ch/cause-effect.php?page=rules) - [Kaggle](https://www.kaggle.com/c/cause-effect-pairs#description)
* [Causal inference datasets in quantitative social sciences](https://github.com/kosukeimai/qss)

# Tools
* [Omega: Causal, Higher-Order, Probabilistic Programming](http://www.zenna.org/Omega.jl/latest/) <img height="16" width="16" color="blue" src="https://julialang.org/assets/infra/logo.svg" />
* [Pyro: A probabilistic programming language built on PyTorch that contains the do() operator](https://pyro.ai) <img height="16" width="16" color="blue" src="https://unpkg.com/simple-icons@latest/icons/python.svg" />
* [Whittemore: Causal Programming in Clojure](https://github.com/jtcbrule/whittemore) <img height="16" width="16" color="blue" src="https://julialang.org/assets/infra/logo.svg" />
* [causaleffect: Functions for identification and transportation of causal effects](https://www.rdocumentation.org/packages/causaleffect) <img height="16" width="16" color="blue" src="https://unpkg.com/simple-icons@latest/icons/r.svg" />
* [pgmpy: Probabilistic Graphical Models in python, extended to causal queries](https://pgmpy.org/inference.html#causal-inference) <img height="16" width="16" color="blue" src="https://unpkg.com/simple-icons@latest/icons/python.svg" />
* [pyagrum: a GRaphical Universal Modeler with causal examples from the Book of Why](https://agrum.gitlab.io/pages/pyagrum.html) <img height="16" width="16" color="blue" src="https://unpkg.com/simple-icons@latest/icons/python.svg" />
* [Counterfactual regression](https://github.com/clinicalml/cfrnet) <img height="16" width="16" color="blue" src="https://unpkg.com/simple-icons@latest/icons/python.svg" />
* [DoWhy - Microsoft Research](https://github.com/Microsoft/dowhy) <img height="16" width="16" color="blue" src="https://unpkg.com/simple-icons@latest/icons/python.svg" />
* [Quantitative Social Science](https://github.com/kosukeimai/qss-package) - [Book](https://github.com/kosukeimai/qss) <img height="16" width="16" color="blue" src="https://unpkg.com/simple-icons@latest/icons/r.svg" />
* [Causal Inference using Bayesian Additive Regression Trees](https://github.com/vdorie/bartCause) <img height="16" width="16" color="blue" src="https://unpkg.com/simple-icons@latest/icons/r.svg" />
* [Non-parametrics for Causal Inference](https://github.com/vdorie/npci) <img height="16" width="16" color="blue" src="https://unpkg.com/simple-icons@latest/icons/r.svg" />
* [Causality by author of Causal Data Science Series (see blogs)](https://github.com/akelleh/causality) <img height="16" width="16" color="blue" src="https://unpkg.com/simple-icons@latest/icons/python.svg" />
* [InvariantCausalPrediction: Invariant Causal Prediction](https://cran.r-project.org/web/packages/InvariantCausalPrediction/index.html) <img height="16" width="16" color="blue" src="https://unpkg.com/simple-icons@latest/icons/r.svg" />
* [Causal Discovery Toolbox](https://github.com/FenTechSolutions/CausalDiscoveryToolbox) <img height="16" width="16" color="blue" src="https://unpkg.com/simple-icons@latest/icons/python.svg" />
* [CausalImpact - causal inference in time series](https://google.github.io/CausalImpact/) <img height="16" width="16" color="blue" src="https://unpkg.com/simple-icons@latest/icons/r.svg" />
* [Daggity - Create causal graphs](http://www.dagitty.net/) <img height="16" width="16" color="blue" src="https://unpkg.com/simple-icons@latest/icons/r.svg" />
* [TETRAD](http://www.phil.cmu.edu/projects/tetrad/) <img height="16" width="16" color="blue" src="https://unpkg.com/simple-icons@latest/icons/java.svg" />
* [ProbLog - Do-calculus](https://dtai.cs.kuleuven.be/problog/tutorial/various/14_robot_key.html) <img height="16" width="16" color="blue" src="https://unpkg.com/simple-icons@latest/icons/python.svg" />
* [Causalnex - A toolkit for causal reasoning with Bayesian Networks](https://github.com/quantumblacklabs/causalnex)
* [Causal Fusion - A web based app for drawing and making inference via do-calculus on causal diagrams](https://causalfusion.net/app)
* [DiCE - Generate Diverse Counterfactual Explanations for any machine learning model](https://github.com/interpretml/dice)
* [CCD Causal Software suite](https://www.ccd.pitt.edu/tools/)
* [The TETRAD Project - searching for causal explanations of data](https://github.com/cmu-phil/tetrad)
* [Causal ML: A Python Package for Uplift Modeling and Causal Inference with ML](https://github.com/uber/causalml)
* [Causality Lab - research code of novel causal discovery algorithms developed at Intel Labs](https://github.com/IntelLabs/causality-lab)

# Learning resources

## Tutorials

* [ICML 2016 Tutorial Causal Inference for Observational Studies](https://cs.nyu.edu/~shalit/tutorial.html)
* [KDD 2018 Causal Inference Tutorial](https://causalinference.gitlab.io/kdd-tutorial/)
* [Joris Mooij ML2 Causality](https://web.archive.org/web/20190312053009/https://drive.google.com/file/d/0B2DZf1QHTotxX2RiNXJ0NUwwekk/edit)
* [Emre Kiciman - Observational Studies in Social Media (OSSM) at ICWSM 2017](https://web.archive.org/web/20180830204832/http://kiciman.org/wp-content/uploads/2016/06/tutorial_kiciman_ossm17.pdf)
* [The Blessings of Multiple Causes: A Tutorial](https://github.com/blei-lab/deconfounder_tutorial)
* [Susan Athey: Counterfactual Inference (NeurIPS 2018 Tutorial)](https://www.youtube.com/watch?v=yKs6msnw9m8) - [Slides](https://web.archive.org/web/20181214003957/https://media.neurips.cc/Conferences/NIPS2018/Slides/Counterfactual_Inference.pdf)
* [Ferenc Huszár Causal Inference Practical from MLSS Africa 2019](https://colab.research.google.com/drive/1rjjjA7teiZVHJCMTVD8KlZNu3EjS7Dmu#scrollTo=h2zDcSPqYuAa) - [\[Notebook Runthrough\]](https://www.youtube.com/watch?v=evmGGusk6gg) [\[Video 1\]](https://www.youtube.com/watch?v=HOgx_SBBzn0) [\[Video 2\]](https://www.youtube.com/watch?v=_RtxTpOb8e4)
* [Causality notes and implementation in Python using statsmodels and networkX](https://github.com/ericmjl/causality)
* [Thinking Clearly About Correlations and Causation: Graphical Causal Models for Observational Data](https://journals.sagepub.com/doi/10.1177/2515245917745629)
* [The Hitchhiker’s Guide to the tlverse or a Targeted Learning Practitioner’s Handbook](https://tlverse.org/tlverse-handbook/)
* [Causal Inference for The Brave and True](https://github.com/matheusfacure/python-causality-handbook)

## Blogs, and Articles

* [Causal Data Science Series](https://medium.com/causal-data-science/causal-data-science-721ed63a4027)
* [Ferenc Huszár Series on Causal Modelling: various parts](https://www.inference.vc/) - [1](https://www.inference.vc/untitled/), [2](https://www.inference.vc/blessings-of-multiple-causes-causal-inference-when-you-cant-measure-confounders/), [3](https://www.inference.vc/causal-inference-2-illustrating-interventions-in-a-toy-example/), [4](https://www.inference.vc/causal-inference-3-counterfactuals/)
* [Diving deeper into causality Pearl, Kleinberg, Hill and untested assumptions](https://yanirseroussi.com/2016/05/15/diving-deeper-into-causality-pearl-kleinberg-hill-and-untested-assumptions/)
* [Simpson's Paradox: An Anatomy](http://bayes.cs.ucla.edu/R264.pdf)
* [Simpson’s paradox and causal inference with observational data](https://roamanalytics.com/2017/09/08/simpsons-paradox-and-causal-inference-with-observational-data/)
* [Causation and Correlation - Talks about possible causes for observed correlations](https://kunalmenda.com/2019/02/21/causation-and-correlation/)
* [(Non-)Identification in Latent Confounder Models](http://www.alexdamour.com/blog/public/2018/05/18/non-identification-in-latent-confounder-models/)
* [Causal Inference Animated Plots - Good explanation of various causal inference methods](http://nickchk.com/causalgraphs.html)
* [Explanation, prediction, and causality: Three sides of the same coin?](https://osf.io/u6vz5/)
* [A chill intro to causal inference via propensity scores](https://osf.io/preprints/socarxiv/ncvqs/)
* [All the DAGs from Hernan and Robins' Causal Inference Book by Sam Finlayson](https://sgfin.github.io/2019/06/19/Causal-Inference-Book-All-DAGs/) - [Causal Inference Book Part I -- Glossary and Notes](https://sgfin.github.io/2019/06/19/Causal-Inference-Book-Glossary-and-Notes/)
* [Causal Inference with Bayes Rule by Gradient Institute](https://gradientinstitute.org/blog/6/)
* [Causal Inference cheat sheet for data scientists](http://nc233.com/2020/04/causal-inference-cheat-sheet-for-data-scientists/)
* [Which causal inference book you should read](https://www.bradyneal.com/which-causal-inference-book)
* [Tweetorial on going from regression to estimating causal effects with machine learning](https://twitter.com/WomenInStat/status/1321595413573464064)
* [Causal Inference in AI Education: A Primer](https://ftp.cs.ucla.edu/pub/stat_ser/r509.pdf) - Accompanying Tool [Learn.CI](https://learn.ci/)
* [The Effect: An Introduction to Research Design and Causality](https://www.theeffectbook.net/index.html)
* [What is Causal Inference and How Does It Work?](https://freecontent.manning.com/what-is-causal-inference-and-how-does-it-work/)

## Books

* [Causal Inference Book](https://www.hsph.harvard.edu/miguel-hernan/causal-inference-book/)
* [Causal Inference in statistics: A primer](http://bayes.cs.ucla.edu/PRIMER/)
* [Elements of Causal Inference - Foundations and Learning Algorithms (includes code examples in R and Jupyter notebooks)](http://web.math.ku.dk/~peters/elements.html)
* [The Book of Why: The New Science of Cause and Effect](http://bayes.cs.ucla.edu/WHY/)
* [Causal Inference Mixtape](http://scunning.com/mixtape.html) - [[R code](https://github.com/scunning1975/mixtape_learnr)] [[Python code](https://github.com/tomcaputo/mixtape_learnr/tree/main/Python)]
* [Elements of Causal Inference - Foundations and Learning Algorithms](https://mitpress.mit.edu/books/elements-causal-inference)
* [Actual Causality By Joseph Y. Halpern](https://www.cs.cornell.edu/home/halpern/papers/causalitybook-ch1-3.html)
* [Causal Reasoning: Fundamentals and Machine Learning Applications by Emre Kiciman and Amit Sharma](https://causalinference.gitlab.io/)
* [The Effect: An Introduction to Research Design and Causality](https://nickchk.com/causalitybook.html)
* [Causal Inference for The Brave and True](https://matheusfacure.github.io/python-causality-handbook/)
* [Bayesuvius: a visual dictionary of Bayesian Networks and Causal Inference](https://www.ar-tiste.com/bayesuvius.html) - [github](https://github.com/rrtucci/Bayesuvius/)
* [Causal Inference for Data Science](https://www.manning.com/books/causal-inference-for-data-science) - [github](https://github.com/aleixrvr/CausalInference4DataScience)
* [Causal Machine Learning](https://www.manning.com/books/causal-machine-learning) - [github](https://github.com/robertness)

## Courses

* [Causal Diagrams: Draw Your Assumptions Before Your Conclusions](https://www.edx.org/course/causal-diagrams-draw-your-assumptions-before-your-conclusions)
* [Causal Inference: prediction, explanation, and intervention](http://www.skleinberg.org/teaching/CI18/index.html)
* [Causal Inference Experiments Short Course](http://www.macartan.nyc/experiment/short-course/)
* [ECON 305: Economics, Causality, and Analytics](http://www.nickchk.com/econ305.html) [\[github\]](https://github.com/NickCH-K/introcausality)
* [Algorithmic Information Dynamics: A Computational Approach to Causality and Living Systems From Networks to Cells](https://www.complexityexplorer.org/courses/63-algorithmic-information-dynamics-a-computational-approach-to-causality-and-living-systems-from-networks-to-cells-2018/)
* [Four Lectures on Causality by Jonas Peters](https://www.youtube.com/playlist?list=PLW01hpWnEtbTcuY0a0jhZyanHX3GPImAy)
* [Julian Schuessler's Causal Graphs Seminar - Winner of 2019 American Statistics Association Causality in Statistics Education Award](http://www.julianschuessler.net/graphs2018.html)
* [Ilya Shpitser's course on Causal Inference (Zip file) - Winner of 2017 American Statistics Association Causality in Statistics Education Award](https://www.amstat.org/asa/files/zipfiles/Causality-ShpitserMaterials.zip)
* [Arvid Sjölander's course on Causal Inference (Zip file) - Winner of 2016 American Statistics Association Causality in Statistics Education Award](https://ww2.amstat.org/misc/causaliity/Sjolander-Supplemental.zip)
* [Onyebuchi A. Arah course on Causality in Statistics (Dropbox folder) - Winner of 2016 American Statistics Association Causality in Statistics Education Award](https://www.dropbox.com/sh/mzuy3bewepwunye/AACn-zaBRAGMvxO-TVtCxH9Ba?dl=0)
* [Introduction to causal inference by Maya L. Petersen & Laura B. Balzer](https://www.ucbbiostat.com/labs)
* [Introduction to Causal Inference by Brady Neal](https://www.bradyneal.com/causal-inference-course)

## Videos

* [PyData LA 2018 Keynote: Judea Pearl - The New Science of Cause and Effect](https://www.youtube.com/watch?v=ZaPV1OSEpHw)
* [CACM Mar. 2019 - The Seven Tools of Causal Inference](https://www.youtube.com/watch?v=CsMV5o3hotY)
* [ACM Turing Award Lecture 2011 - Judea Pearl](https://amturing.acm.org/vp/pearl_2658896.cfm)
* [Leon Bottou - Learning representations using causal invariance](https://www.facebook.com/iclr.cc/videos/534780673594799/)
* [Online Causal Inference Seminar](https://www.youtube.com/channel/UCiiOj5GSES6uw21kfXnxj3A/videos)
* [NeurIPS 2020 Workshop: Causal Discovery and Causality-Inspired Machine Learning](https://nips.cc/virtual/2020/protected/workshop_16110.html)
* [Okke van der Wal - Personalization at Uber scale via causal-driven machine learning | PDAMS 2023](https://www.youtube.com/watch?v=c_dOpCvkNc0&t=672s&ab_channel=PyData)

# Events

## Workshops
* [Beyond Curve Fitting: Causation, Counterfactuals, and Imagination-based AI](https://why19.causalai.net/#)
* [Causality Challenge #1: Causation and Prediction](http://www.causality.inf.ethz.ch/challenge.php)
* [NIPS 2013 Workshop on Causality](http://clopinet.com/isabelle/Projects/NIPS2013/)
* [ChaLearn Fast Causation Coefficient Challenge](https://competitions.codalab.org/competitions/1381)


# Communities, and Mailing lists

* [Causality Challenge Google group](https://groups.google.com/forum/#!forum/causalitychallenge)


# Miscellaneous

* [Causal Inference Reading list](https://yanirseroussi.com/causal-inference-reading-list/)
* [Causal inference paper reading list](https://web.archive.org/web/20190312230219/https://www.reddit.com/r/MachineLearning/comments/8lti7g/d_ml_beyond_curve_fitting_introduction_to_causal/dzipydw/)
* [American Statistics Association Causality in Statistics Education Award](https://www.amstat.org/ASA/Your-Career/Awards/Causality-in-Statistics-Education-Award.aspx)

