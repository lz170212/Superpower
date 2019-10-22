NEWS
================

Updates from contrast\_extension update Sat Oct 19 2019

\-Added estimated marginal means comparisons using `emmeans` R package.
-`emm = TRUE` in the ANOVA\_power, ANOVA\_exact, and plot\_power will
result in emmeans being calculated -Default is all pairwise comparisons
but this can be modified with `contrast_type` and `emm_comp` options

\-Add global options -Options that have crossover between functions can
now be set globally for the package -Includes: verbose, emm, emm\_model,
contrast\_type, alpha\_level, and plot -These global options can be seen
with Superpower\_options()

\-Updated Shiny Apps -Now includes emmeans options -kableExtra, emmeans,
magrittr, and dplyr packages now needed to knit markdown file in app.