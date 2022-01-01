# EC122 Practice Exercises

A set of practice questions to accompany EC122 lecture materials.

Practice exercises are written using `learnr`. A standalone package is created `ec122practiceq`. This is also hosted on `mybinder.org` for easy access.

**steps to generate exercises**

- create the exercise in `learnr`
- check if the exercise is error free: e.g. `learnr::run_tutorial("lesson1", package = "ec122practiceq")`
- `Ctrl+Shift+B` to Build>Install and Restart the package
- push changes to `subhamk/ec122practiceq`
- copy the `.Rmd` file to `subhamk/ec122practiceqbind/lesson1`
- push changes to `subhamk/ec122practiceqbind`
- Launch RStudio in binder and `Run the document` after navigating to the relevant folder: [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/subhamk/ec122practiceqbind/HEAD?urlpath=rstudio)
- Each exercise runs as a shiny app. Get the direct link to share. For Lesson 1 exercise [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/subhamk/ec122practiceqbind/HEAD?urlpath=shiny/lesson1/)
