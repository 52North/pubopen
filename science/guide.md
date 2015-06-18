<div class="panel panel-info">
    <div class="panel-heading">
        <h3 class="panel-title"><i class="octicon octicon-megaphone"></i> Guide: Do software "right" from the start</h3>
    </div>
    <div class="panel-body">
        <p>You can greatly improve the quality of the code and by that <em>of your research work</em> by following established practices of the language of your choice form the start. The important part here is <b>from the start</b>: Spending small efforts in (a) setting up a reproducible dependency and build system in the beginning and (b) documenting the software all the time is a lot easier than trying to add the documentation or "overhaul" after the fact when the code is "finished". <i class="octicon octicon-alert"></i> Code is never finished. Seemingly simple information, such as how to set up the environment, or versions of used libraries, is simply lost after code is unused for a few months.</p>
        
        <ul>
            <li>Read a minimum of software development principles so that you know where you can find help. No need to actually learn someting you can always look up!</li>
            <li>Don't reinvent the wheel, use established libraries</li>
            <li>Use established build and dependency management solutions for your language of choice, and even if you don't plan to publish your code to public repositories, do package it for them because it will enforce good practices.
            <ul>
                <li>use <a href="http://maven.apache.org/">Maven</a> or <a href="">Gradle</a> for <b>Java</b></li>
                <li>write an <a href="htt</a>p://cran.r-project.org/doc/manuals/R-exts.html">extension package</a> for <i class="octicon octicon-heart"></i> <b>R</b> and load required packages from <a href="http://cran.r-project.org/">CRAN</a></li>
                <li>write a <a href="https://pypi.python.org/pypi">PyPi</a> module when using <b>Python</b>
                <li>use <a href="">Grunt</a> and <a href="http://bower.io/">Bower</a> for <b>JavaScript</b>, and package your code in an <a href="https://www.npmjs.com/">NPM module</a></li>
                <!--<li><b>Matlab</b>?</li>-->
            </ul>
            <li>Document constanctly - use "future you" without any previous knowledge as the recipient to judge level of detail of documentation</li>
            <li>Use a common documentation solution - see [Documentation](./communities/documentation.md).
        </ul>
    </div>
    <div class="panel-footer">
        <i class="octicon octicon-comment-discussion"></i> Do you know typical frameworks for other languages used in open source development?
    </div>
</div>

