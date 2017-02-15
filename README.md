# Kording lab teaching 2016

Repository to stores link, materials, code snippets for Kording lab teaching 2016.
See teaching details on [kordinglab.com/lab_teaching_2016](http://kordinglab.com/lab_teaching_2016/).
We will put details for each session in separate folder including code, slides or link to slides.
If slides is larger than 1 MB, we recommend to put the link to
the slide instead of putting the whole pdf on repository directly.
Feel free to update or pull request!


## Edit the page

You can edit page on `docs` folder on the repository. Custom `docs/_data/project.yml`
to add information of the talk. Each talk can be added into `_data/project.yml`
in the format as follows:

```
- name: "Oct 25th, Introduction on XGBoost"
  link: session_2
  description: "Introduction on XGBoost (extreme gradient boosting) and example code in Python by Titipat"
```

Typically, we will stick creating the slide using [`remarkjs`](https://github.com/gnab/remark),
you can put slide (which is `index.html`) to new folder e.g. `session_2`.
Editing this page will show up at [kordinglab.com/lab_teaching_2016](http://kordinglab.com/lab_teaching_2016/).

## Run Jekyll page locally

You can change directory to `docs` folder then run

```
jekyll serve
```

to serve on local machine
