# <i class="octicon octicon-megaphone"></i> Guide: Do software "right" from the start

You can greatly improve the quality of code and <em>of your research</em> by following established practices of the language of your choice **from the start**. Spend a little bit of effort in (a) setting up a reproducible dependency and build system in the beginning and (b) documenting the software all the time. This is a lot easier than trying to add documentation or "overhaul" when the code is "finished". <i class="octicon octicon-alert"></i> Code is never finished. Seemingly simple information, such as how to set up the environment, or versions of used libraries, is simply lost after code is unused for a few months.

* Read a minimum of software development principles so that you know where you can find help. No need to learn something you can look up!
* Don't reinvent the wheel, use established libraries.
* Use established build and dependency management solutions for your language of choice. Even if you don't plan to publish your code in public repositories, do package it for them because it will enforce good practices.
  * use <a href="http://maven.apache.org/">Maven</a> or <a href="">Gradle</a> for <b>Java</b>
  * write an <a href="htt</a>p://cran.r-project.org/doc/manuals/R-exts.html">extension package</a> for <i class="octicon octicon-heart"></i> <b>R</b> and load required packages from <a href="http://cran.r-project.org/">CRAN</a>
  * write a <a href="https://pypi.python.org/pypi">PyPi</a> module when using <b>Python</b>
  * use <a href="">Grunt</a> and <a href="http://bower.io/">Bower</a> for <b>JavaScript</b>, and package your code in an <a href="https://www.npmjs.com/">NPM module</a>
<!--<li><b>Matlab</b>?</li>-->
* Document constantly
  * use "future you" without any previous knowledge as the recipient to judge level of detail of documentation
  * use a common documentation solution - see [Documentation](./science/documentation.md)


<i class="octicon octicon-comment-discussion"></i> Do you know typical frameworks for other languages used in open source development?
