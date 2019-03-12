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
* [Amazon Review Sales](https://github.com/rguo12/CIKM18-LCVA) [Google drive](https://drive.google.com/drive/u/1/folders/1Ff_GdfjhrDFbZiRW0z81lGJW-cUrYmo1) [Paper](https://arxiv.org/abs/1808.03333)
* [Jobs Training](http://users.nber.org/~rdehejia/data/nswdata2.html) - [Train](http://www.fredjo.com/files/jobs_DW_bin.train.npz) [Test](http://www.fredjo.com/files/jobs_DW_bin.test.npz) [Paper](http://proceedings.mlr.press/v70/shalit17a.html)
* [Twins](https://github.com/AMLab-Amsterdam/CEVAE/tree/master/datasets/TWINS)
* [Synthetic IHDP](https://github.com/AMLab-Amsterdam/CEVAE/tree/master/datasets/IHDP)
* [2016 Atlantic Causal Inference competition](https://github.com/vdorie/aciccomp/tree/master/2016)
* [News trearment effect measurement](http://www.fredjo.com/files/NEWS_csv.zip)
* [Cause effect pairs](http://webdav.tuebingen.mpg.de/cause-effect/)
* [Movie recommendations - Missing not at random (MNAR)](http://www.cs.cornell.edu/~schnabts/mnar/index.html) [Paper](http://proceedings.mlr.press/v48/schnabel16.html)
* [CHALEARN Fast Causation Coefficient Challenge](http://www.causality.inf.ethz.ch/cause-effect.php?page=rules) [Kaggle](https://www.kaggle.com/c/cause-effect-pairs#description)
* [Causal inference datasets in quantitative social sciences](https://github.com/kosukeimai/qss)

# Tools

* [Counter factual regression](https://github.com/clinicalml/cfrnet) <img height="16" width="16" color="blue" src="https://unpkg.com/simple-icons@latest/icons/python.svg" />
* [DoWhy - Microsoft Research](https://github.com/Microsoft/dowhy) <img height="16" width="16" color="blue" src="https://unpkg.com/simple-icons@latest/icons/python.svg" />
* [Quantitative Social Science](https://github.com/kosukeimai/qss-package) [Book](https://github.com/kosukeimai/qss) <img height="16" width="16" color="blue" src="https://unpkg.com/simple-icons@latest/icons/r.svg" />
* [Causal Inference using Bayesian Additive Regression Trees](https://github.com/vdorie/bartCause) <img height="16" width="16" color="blue" src="https://unpkg.com/simple-icons@latest/icons/r.svg" />
* [Non-parametrics for Causal Inference](https://github.com/vdorie/npci) <img height="16" width="16" color="blue" src="https://unpkg.com/simple-icons@latest/icons/r.svg" />
* [Causality by author of Causal Data Science Series (see blogs)](https://github.com/akelleh/causality) <img height="16" width="16" color="blue" src="https://unpkg.com/simple-icons@latest/icons/python.svg" />
* [InvariantCausalPrediction: Invariant Causal Prediction](https://cran.r-project.org/web/packages/InvariantCausalPrediction/index.html) <img height="16" width="16" color="blue" src="https://unpkg.com/simple-icons@latest/icons/r.svg" />
* [Causal Discovery Toolbox](https://github.com/Diviyan-Kalainathan/CausalDiscoveryToolbox) <img height="16" width="16" color="blue" src="https://unpkg.com/simple-icons@latest/icons/python.svg" />


# Learning resources

## Tutorials

* [ICML 2016 Tutorial Causal Inference for Observational Studies](https://cs.nyu.edu/~shalit/tutorial.html)
* [KDD 2018 Causal Inference Tutorial](https://causalinference.gitlab.io/kdd-tutorial/)
* [Joris Mooij ML2 Causality](https://web.archive.org/web/20190312053009/https://drive.google.com/file/d/0B2DZf1QHTotxX2RiNXJ0NUwwekk/edit)
* [Emre Kiciman - Observational Studies in Social Media (OSSM) at ICWSM 2017](https://web.archive.org/web/20180830204832/http://kiciman.org/wp-content/uploads/2016/06/tutorial_kiciman_ossm17.pdf)
* [The Blessings of Multiple Causes: A Tutorial](https://github.com/blei-lab/deconfounder_tutorial)
* [Susan Athey: Counterfactual Inference (NeurIPS 2018 Tutorial)](https://www.youtube.com/watch?v=yKs6msnw9m8) [Slides](https://web.archive.org/web/20181214003957/https://media.neurips.cc/Conferences/NIPS2018/Slides/Counterfactual_Inference.pdf)



## Blogs, and Articles

* [Causal Data Science Series](https://medium.com/causal-data-science/causal-data-science-721ed63a4027)
* [Ferenc Huszár Series on Causal Modelling: various parts](https://www.inference.vc/) [1](https://www.inference.vc/untitled/) [2](https://www.inference.vc/blessings-of-multiple-causes-causal-inference-when-you-cant-measure-confounders/) [3](https://www.inference.vc/causal-inference-2-illustrating-interventions-in-a-toy-example/) [4](https://www.inference.vc/causal-inference-3-counterfactuals/)
* [Diving deeper into causality Pearl, Kleinberg, Hill and untested assumptions](https://yanirseroussi.com/2016/05/15/diving-deeper-into-causality-pearl-kleinberg-hill-and-untested-assumptions/)
* [Simpson's Paradox: An Anatomy](http://bayes.cs.ucla.edu/R264.pdf)
* [Simpson’s paradox and causal inference with observational data](https://roamanalytics.com/2017/09/08/simpsons-paradox-and-causal-inference-with-observational-data/)

## Books

* [Causal Inference Book](https://www.hsph.harvard.edu/miguel-hernan/causal-inference-book/)
* [Causal Inference in statistics: A primer](http://bayes.cs.ucla.edu/PRIMER/)
* [Elements of Causal Inference - Foundations and Learning Algorithms (includes code examples in R and Jupyter notebooks)](http://web.math.ku.dk/~peters/elements.html)
* [The Book of Why: The New Science of Cause and Effect](http://bayes.cs.ucla.edu/WHY/)

## Courses 

* [Causal Diagrams: Draw Your Assumptions Before Your Conclusions](https://www.edx.org/course/causal-diagrams-draw-your-assumptions-before-your-conclusions)
* [Causal Inference: prediction, explanation, and intervention](http://www.skleinberg.org/teaching/CI18/index.html)
* [Causal Inference Experiments Short Course](http://www.macartan.nyc/experiment/short-course/)

## Videos

* [PyData LA 2018 Keynote: Judea Pearl - The New Science of Cause and Effect](https://www.youtube.com/watch?v=ZaPV1OSEpHw)
* [CACM Mar. 2019 - The Seven Tools of Causal Inference](https://www.youtube.com/watch?v=CsMV5o3hotY)
* [ACM Turing Award Lecture 2011 - Judea Pearl](https://amturing.acm.org/vp/pearl_2658896.cfm)

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
