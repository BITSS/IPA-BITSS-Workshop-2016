README for the Markdoc Demo
===========================

This folder contains files for the Markdoc Demo. Markdoc is a tool to write dynamic documents in Stata.

###What:
Dynamic documents contain analysis code and output all in one document. The old way people worked (and sadly, the way most people still work) is by having a bunch of analysis script files (.do files in Stata, or .R files in R), which would produce a bunch of output files (figures, graphs, tables, etc.) and a separate file for the final paper. 

###Why:
*Hopefully* people at least automate this process to the point where they run their scripts, and then automatically include the latest output in the paper (which can be done without too much difficulty in LaTeX--for examples, see files from [this Github repo](https://github.com/BITSS/UCSDWorkshop/tree/master/Rmarkdown) for a previous workshop I led. But people are probably not even doing that, especially if they're writing in Word. You can include references to files in Word, but it's kind of a pain, so people are probably just inserting images or copying and pasting, which you have to remember to do every time you update the figures. Once you have more than one or two figures to insert and keep updating, it becomes very hard to keep track of which script files generated which output (and it is straight up impossible for reviewers or anyone other than the original author to determine this.) Dynamic documents are the solution to this problem.

Basically, dynamic documents are a file that contains interspersed bits of code and your final paper.  Code chunk1 that generates Figure 1, intro paragraph of paper that cites Figure 1, code chunk 2, paper paragraph 2, etc. (It's much easier with an example--see the other files in this repo.)

The best dynamic documents software out there is easily R Markdown, which works with R. You can write your entire paper in R Markdown: figures, citations, everything. 

The option for Stata users is Markdoc. To install, type "ssc install markdoc" in Stata. Also run "adoupdate" because markdoc is a work in progress.
