# Homework 2

## Collect All Four

Some brands of cold cereal run promotions in which one of four free toys
is included in the cereal box. The company encourages consumers to "collect all
four." The typical approach is to buy one box at a time and stop as soon as the
set is complete. Consider two scenarios: 1. That each toy is equally likely,
and 2. That toys have selection probabilities 0.10, 0.25, 0.25, and 0.40. Write
an R script or RMarkdown document named `all-four.R` (or `all-four.Rmd`) which 
conducts a Monte Carlo simulation study to answer the following questions under 
the two scenarios:

  * What is the mean number of boxes that a consumer must purchase to get a complete set?
  * What proportion of consumers will need to purchase 14 boxes or more to complete a set?

In answering the questions, **be sure to assess the Monte Carlo error (through a
confidence interval)**. Your script should run in less than about 30 seconds.
Use good coding standards, such as proper indentation and good variable names.
Make your script reuse as much code as possible, as opposed to having
virtually-duplicated code with only minor modifications. Make sure your code
clearly labels and displays the results rather than just printing out numbers.
Note that, in this problem, the number of items in the set is 4. The best
solution is general for any number of items in the set, that is, it is best if
the code can handle selection probabilities vectors of arbitrary length.
Summarize your results in a file called `memo.txt` that would be appropriate to
share with your boss who doesn't know R.


## Birthday Problem

The [birthday problem](https://en.wikipedia.org/wiki/Birthday_problem) is
described in [Wikipedia](https://www.wikipedia.org/).  Briefly, it concerns the
probability that, among n randomly chosen people, some pair of them will have
the same birthday.  For simplicity, ignore the possibility of leap day
(February 29). In a script named `birthday.R` or `birthday.Rmd`, write an R 
function called `birthday` that takes two arguments: `n` (a numeric vector of 
length one giving the number of people) and `n_reps` giving the number of replications
for thsimulation study.  The function should return a numeric vector of length 
three giving a Monte Carlo estimate and a 95% confidence interval on the probability.

Plot your Monte Carlo estimates of this probability (on the y-axis) as a
function of n (on the x-axis) using a solid black line.  With dashed lines,
show the lower and upper bounds of your 95% confidence intervals.  With a red
line, show the true probability based on the formula for the Wikipedia article.
Your plot should look like [this](birthday.pdf) (subject to Monte Carlo error).
Do not submit your plot as part of the homework, but do submit the R code that
produces your plot.

**There is no additional step necessary to turn in your homework. Simply create
the scripts described above and save your work in RStudio Cloud. Remember not
to edit or access your homework after the due date or it may be considered a
late submission.**
