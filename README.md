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

See teaching details on [kordinglab.com/lab_teaching_2016](http://kordinglab.com/lab_teaching_2016/)
