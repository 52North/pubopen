# Fork & Pull Workflow

Even when you work with only two people, we  highly recommend the "Fork & Pull" development model. 
From the [GitHub help on pull requests](https://help.github.com/articles/using-pull-requests/):

> *The fork & pull model lets anyone fork an existing repository and push changes to their personal fork without requiring access be granted to the source repository. The changes must then be pulled into the source repository by the project maintainer. This model reduces the amount of friction for new contributors and is popular with open source projects because it allows people to work independently without upfront coordination.*

<!--One "main" repository coordinates the forks of all developers.

It means that in the network of distributed Git repositories, there is one "main" repository that is used to coordinate the forks of all the developers. Even the "main contributor" has a fork and works mainly within that fork.


You can "transport" work from one fork to another (often the upstream repo) using pull requests and merge the code in the web browser. IfYou don't know yet what "upstream", "pull" or "merge" means? Then jump ahead right now to the "Further reading" below and read the glossary!

A pull request inverts the direction of the pull from one Git repository to another: Instead of you fetching and merging changes into your own repository, you're notifying someone else: "Hey, look at this and please integrate it into your fork!"
-->


The advantages are also true for projects with close collaboration, i.e. where there is a lot of upfront coordination, maybe even within the same office space:

* Everybody can do what they want within their fork.
* Changes to the main repo can be *discussed and reviewed* within the pull requests.
* Access control to the main repository are with the project maintainer.
* Pull requests work between any of the forks.


**Bootcamp articles:**

* [Fork a Repo](https://help.github.com/articles/fork-a-repo/)
 
**Further reading:**

* [GitHub Glossary](https://help.github.com/articles/github-glossary/)
* [Using pull requests](https://help.github.com/articles/using-pull-requests/)



<!--
## Excursion: Forking used to be a critical event

“Forking” of code (and community)
http://en.wikipedia.org/wiki/Fork_%28software_development%29
http://en.wikipedia.org/wiki/List_of_software_forks: LibreOffice from OpenOffice.org
-->