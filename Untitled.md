Research and Data Analysis Seminar - Stata Introduction
================
19th to 23rd September 2022







## Class 1: General introduction

The first simple thing you can do with Stata is to use it as a
calculator:

    display 2+5
    display 4*5
    display sqrt(9)
    display 4^2 + log(1) + sqrt(9)

If you try to run these lines of code on your computer you get the
corresponding arithmetic results. Of course, Stata (and any other
computational software) is not used as a calculator. However, `display`
command is quite important as it displays strings and values of scalar
expressions. For example:

    display "The result is:" 2 + 2

will return: `The result is: 4`. Therefore, whenever you want to display
some output use `display`. <br/>

### General common syntax

You may probably got the Stata syntax pattern, but more formally it is
the following:

    command variable(s), options

where the command is the name of the required/needed command
(e.g.,`display`), the variable(s) is(are) the variable(s) to which we
want to apply the specified command/formula. *The order of the
variable(s) may matter!*. Lastly, options are details that can be
supplied to the provided command. <br/>

However, for any doubts about the correct syntax for a specific command
and its options the `help` command is our friend!

    help display

will explain you the features, meaning, syntax and eventually options.
For example, if you type `help display`, do you find anything about
options?
