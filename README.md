# Kording lab teaching 2016

Repository to stores link, materials, code snippets for Kording lab teaching 2016.
We will put details for each session in separate folder including code, slides or link to slides.
If slides is larger than 1 MB, we recommend to put the link to
the slide instead of putting the whole pdf on repository directly.
Feel free to update or pull request!


## Edit page

You can edit page on [`gh-pages`](https://github.com/KordingLab/lab_teaching_2016/tree/gh-pages)
branch for Kording lab teaching 2016. This page will show up at [kordinglab.com/lab_teaching_2016](http://kordinglab.com/lab_teaching_2016/).

To add slide, for example [`remarkjs`](https://github.com/gnab/remark),
you can put slide (which is `index.html`) to new folder e.g. `session_2`.
Then custom `_data/project.yml` to add information of the talk so that others can
access the slides online from [kordinglab.com/lab_teaching_2016](http://kordinglab.com/lab_teaching_2016/).

Each talk can be added into `_data/project.yml` in the format as follows

```
- name: "Oct 25th, Introduction on XGBoost"
  link: session_2
  description: "Introduction on XGBoost (extreme gradient boosting) and example code in Python by Titipat"
```


## Teaching and talks

### Session 1

[Max Berniker](http://sensorimotorcontrolatorium.uic.edu/), lab alumnae and professor
at University of Illinois at Chicago. October 18th 3-4 PM.
Max will cover updates new research at the lab and _Normative Models of Network Activity_


### Session 2

[Titipat Achakulvisut](http://kordinglab.com/people/titipat_achakulvisut/index.html), Tutorial on [`XGBoost`](https://github.com/dmlc/xgboost)
(extreme gradient boosting library for Python). October 25th 3-4 PM. Titipat will cover basic of Gradient Boosting algorithm.
Parameters in `XGBoost` and basic usage of `XGBoost`.


### Session 3

[Eva Dyer](http://kordinglab.com/people/eva_dyer/index.html) will give her practice her
neurosciency talk for Machine learning audience and then talk about challenges in
neural data analysis. This will happen on November 1st at 1.30 PM


### Session 4

[Roozbeh Farhoodi](http://kordinglab.com/people/roozbeh_farhoodi/index.html)
on Generative Adversarial Networks (GAN) on November 8th 3-4 PM. GAN is a very popular
deep learning framework that consists of 2 components: discriminative model `D`
and generative model `G`. He'll go through some math and gist behind GAN.


### Session 5

[Ari Benjamin](http://kordinglab.com/people/ari_benjamin/index.html) on Gradient Descent on November 15th 3-4 PM.
Ari will teach us about [optimization technique in Deep learning](http://www.deeplearningbook.org/contents/optimization.html) including popular Stochastic Gradient Descent (SGD), Momentum technique, RMSProp, AdaGrad,
Adam, Approximate Second Order method, Conjugate gradient method (and more).
Plus some coding example on how to apply these optimization.


### Session 6

[Ravi Garg](http://kordinglab.com/people/ravi_garg/index.html), Tutorial on [Docker](https://www.docker.com/) on November 22nd 3-4 PM, containers that  wrap a piece of software in an environment.
