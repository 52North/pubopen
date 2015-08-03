# Scope and Goals

Research of today is driven by (sometimes large amounts of) data from various sources and of manifold aspects. Often this data is published as "open" data and within research projects. It is analyzed with general and expert software written by informaticians and domain scientists alike. The projects have a life span of 2 to 4 years. Often this software is deemed unfit for publication, although the idea of open source software is widespread. Too often though **the reason for not publishing the software is lack of time or knowledge**. This best practice will provide arguments and workflows that allow an effective and cost-worthy publication as well as long-term maintenance and management of research software as open source software.

The **target audience** is project managers, work group leaders, and scientists from all domains that use code for their research but have not yet published it. The document provides a quick overview into relevant topics and provides references to more detailed work. The authors aim to use plain language to explain technical topics, but also introduce you to the "lingo" of open source software development. Where useful we add **<i class="octicon octicon-megaphone"></i> Open Guides** to approach a topic from a very opinionated standpoint to answer the most relevant questions for practical applications.

On the one hand, the goal of this publication is to give research project leaders, principal investigators, and researchers a set of workflows that increase the amount of reusable open source software to optimize research and its impact, as well as arguments for negotiations with supervisors or funding agencies that argue in favour of a publication.
On the other hand, the experiences behind this work come from participation of an open source initiative and small enterprise, which uses open source software as its means of doing applied research in the geoinformatics domain, in funded research projects. These experiences are put into writing for the first time to improve the process of doing problem-driven research within such an organisation.

We cannot cover specifc programming languages or recommend specific libraries of application domains, such as hydrology, physics, or geomorphology. Please feel free to <i class="octicon octicon-comment-discussion"></i> contribute such information as chapters to this document.

<!-- https://octicons.github.com/ -->
As you might have noticed, we try to use icons in the text to show when content is <i class="octicon octicon-alert"></i> important, up for <i class="octicon octicon-comment-discussion"></i> discussion, our <i class="octicon octicon-megaphone"></i> opinion, covers <i class="octicon octicon-law"></i> legal aspects, especially relevant for <i class="octicon octicon-mortar-board"></i> PhD students, based on <i class="octicon octicon-link-external"></i> external resources or <i class="octicon octicon-quote"></i> quotes, related to <i class="octicon octicon-pencil"></i> scientific publications, covers <i class="octicon octicon-pulse"></i> new or <i class="octicon octicon-flame"></i> "hot" but naturally unestablished topics, <i class="octicon octicon-comment-discussion"></i> open for discussion or your contributions are needed, or we simply <i class="octicon octicon-heart"></i> really like it.

<!-- http://styleguide.gitbook.com/ -->

---

## <i class="octicon octicon-megaphone"></i> Guide: Should I publish my code, when, and what part of it?</h3>

In short... <b>yes, publish reusable abstract core functions from the start.</b>

You should not publish your code as part of a "dissemination" for "others to use" at the end of your work. If you don't plan to continue working on something, don't use open-sourcing to silence your conscience.
        
By publishing your code you can effectively...
* demonstrate scientific rigor.
* improve the quality of the code and subsequently your research.
* start collaborations with other researchers.
* ...

The most crucial question is what part of the code should be published. Publish reusable partitions / core libraries / abstract functionality, instead of "solution" to your own problem. The solution to your problem is of course still integrated in the code, but as one of potentially many applications. This allows other to re-use your code, contribute to improve it, and you to take advantage of their improvements.

If possible, you should not start a new project at all but identify an existing solution, framework or community and contribute your new work to it. If you have a valid contribution and can maintain it for some time, any community will welcome you with open arms.
        
The guides in this book apply to different degrees both to very small projects, such as a new algorithm for a specific problem in biochemistry, to large ones, such as a new cloud-based communication framework for the next generation of internet of things sensor nodes.

<i class="octicon octicon-comment-discussion"></i> This is an opinionated view. What are your experiences? Get in touch and contribute!</p>

**Further resources**
* https://wiki.52north.org/bin/view/Documentation/BestPracticeOpenSourceForUniversityResearchers

---