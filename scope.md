# Scope and Goals

Research today is driven by data. It comes from various sources and is of manifold aspects. Often this data is published and analyzed as "open" data out of research projects ranging from single thesis to international consortium. Such projects have a life span of 2 to 4 years. Often the software developed for analysis is deemed unfit for publication, although the idea of open source software is widely known. Too often **the reason for not publishing the software is lack of time or knowledge**. This best practice will provide arguments and workflows that encourage effective and cost-efficient publication, as well as ensure long-term maintenance and management of research software as open source software.

The **target audience** is project managers, work group leaders and scientists from all domains that use code for their research but have not yet published it. The document provides an overview of relevant topics and provides references to more detailed work. The authors aim to use plain language to explain technical topics, but also introduce the "lingo" of open source software development. Where useful we add **<i class="octicon octicon-megaphone"></i> Open Guides** to approach a topic from an opinionated standpoint to answer the most relevant questions for practical applications.

The **goal of this publication** is to give research project leaders, principal investigators, and researchers a set of workflows that increase the amount of reusable open source software to optimize research and its impact. It also provides arguments for publication when  negotiating with supervisors or funding agencies.
Please note that it is based on an open source initiative/small enterprise's experience in funded research projects. Open Source software is used while doing applied research in the geoinformatics domain.

We cannot cover specifc programming languages or recommend specific libraries of application domains, such as hydrology, physics, or geomorphology. But we think such recommendations would be useful, so please feel free to <i class="octicon octicon-comment-discussion"></i> contribute such information as chapters to this document.

<!-- https://octicons.github.com/ -->
We use icons in the text to show when content is <i class="octicon octicon-alert"></i> important, up for <i class="octicon octicon-comment-discussion"></i> discussion, an <i class="octicon octicon-megaphone"></i> opinion, covers <i class="octicon octicon-law"></i> legal aspects, especially relevant for <i class="octicon octicon-mortar-board"></i> PhD students, based on <i class="octicon octicon-link-external"></i> external resources or <i class="octicon octicon-quote"></i> quotes, related to <i class="octicon octicon-pencil"></i> scientific publications, covers <i class="octicon octicon-pulse"></i> new or <i class="octicon octicon-flame"></i> "hot" topics, <i class="octicon octicon-comment-discussion"></i> open for discussion or your contributions are needed, or we simply <i class="octicon octicon-heart"></i> really like it.
<!-- http://styleguide.gitbook.com/ -->

---

## <i class="octicon octicon-megaphone"></i> Guide: Should I publish my code, when, and what part of it?

<b>Yes, publish reusable abstract core functions from the start.</b> Don't publish your code as part of a "dissemination" for "others to use" at the end of your work. ~~If you don't plan to continue working on something, don't use open-sourcing to silence your conscience.~~
        
By publishing your code you can effectively
* demonstrate scientific rigor,
* improve the quality of the code and subsequently your research,
* start collaborations with other researchers.

*What part of the code should be published?* Publish reusable partitions / core libraries / abstract functionality, instead of the "solution" to your own problem. This allows others to re-use your code and contribute to improve it, and you to take advantage of their improvements. Your requirements are still met by the published code, even though you might actually work in a derived specialized project.

If possible, do not start a new project, but identify an existing project, framework or community and contribute your new work to it. If you have a valid contribution and can maintain it for some time, any community will welcome you with open arms.
        
The guides in this book apply both to very small projects, such as a new algorithm for a specific problem in biochemistry, and to large ones, such as a new cloud-based communication framework for the next generation of the internet of thing's sensor nodes.

<i class="octicon octicon-comment-discussion"></i> This is an opinionated view. What is your experience? Get in touch and contribute!</p>

**Further resources**
* https://wiki.52north.org/bin/view/Documentation/BestPracticeOpenSourceForUniversityResearchers

---
