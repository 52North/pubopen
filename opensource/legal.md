# Legal Stuff

Your read right: "<i class="octicon octicon-law"></i> stuff". That shows how gingerly you should pick up the contents of this section. As the nerd says: ["IANAL"](https://en.wikipedia.org/wiki/IANAL) - I am not a laywer, and while we have some experiences with open sources licensing, we cannot give you the professional advice that your require. There are many different legal systems in the world, and if you are in doubt about anything, then get a lawyer or get in touch with colleagues and your legal department, if you have access to one.

Seriously, there is now way around contacting a lawyer specializing in open source licenses if you are unsure about legal matters regarding your open source software or software that you use.

That said, there is a plethora of guides and opinions available online and in books, and several resources exist that cover all typical cases to the extent that a non-expert can be as sure as she can about important questions such as license compatibility.

In the remainder of this section we introduce some that we found most accessible and useful and try to summarize the matter for the most typical scenarios.


## Basics

### Copyright

&copy;

[Copyright](http://en.wikipedia.org/wiki/Copyright) is a legal concept that gives the creator of a work certain rights to (exclusively) use that work, grant permissions to other persons, etc. It is intended to protect the creator(s) from economical and ideological abuse of their works. You, as a creator have the copyright by default and usually you can determine under which conditions your work may be used by others. However, the exact scope, which rights a creator of a work has, depends on the specific applicable law (e.g. the copyright laws of specific countries).

Please note that there are also limitations regarding the copyright, which grant some exceptions for specific cases. This is referred as “fair use”. To get an overview, we recommend this [Wikipedia article](https://en.wikipedia.org/wiki/Fair_use). Other limitations concern the exhaustion of the copyright after certain periods (depending on the specific laws).

Finally, copyright requires that you have created some work that has a certain threshold of originality. However, this threshold is generally rather low. An interesting discussion about this topic can be found [here](http://softwarefreedom.org/resources/2007/originality-requirements.html).

Finally, some history: In the old Roman Empire and the mediaeval ages, there was no copyright. At that time it took extremely high efforts to copy a text so that this was not really an issue. However, with the invention of the letterpress this changed. For example this has led to the “Printer’s Privilige” Act of 1709, also known as the Statute of Anne (British law). Other examples are the Droit d’auteur (France, 1793: authors want acknowledgement not money) or the German Urheberrechtsgesetz (UrhG) from 1965. You can find a detailed overview on the history of the copyright on [Wikipedia](http://en.wikipedia.org/wiki/History_of_copyright_law).


### Copyleft

<img src="https://upload.wikimedia.org/wikipedia/commons/8/8b/Copyleft.svg" width="48">

If you want to make your work free, you might also want that any modification or extensions of this work shall be free. This concept is also called “copyleft”.  This means that you can use the copyleft as a method to ensure that your software is free and that all modifications and extensions of your code have to be free, too. GNU explains this as follows: *"Proprietary software developers use copyright to take away the users' freedom; we use copyright to guarantee their freedom. That's why we reverse the name, changing 'copyright' into 'copyleft.'”* (http://www.gnu.org/copyleft/copyleft.html).

When talking about copyleft, we need to distinguish different types of copyleft. Generally, we can see three main categories:
* Strong copyleft requires all derived work to inherit the original copyleft license
* Weak copyleft refers to licenses, which do require not for all derived work that it inherits the copyleft license. For example, you may link your software to a weak copyleft licensed library without using the same license. But if you change the original software, the copyleft license needs to be kept. This is for example useful if you want to publish libraries that shall be re-usable by a broad range of other projects.
* Non-copyleft does not have requirements on the license of derived software.
As you will see later on, the different types of copyleft are an important factor when choosing an open source license for your software.

If you would like to learn more about copyleft, we recommend the following resources:
* http://www.gnu.org/copyleft/
* http://en.wikipedia.org/wiki/Copyleft
* http://www.visionmobile.com/blog/2011/03/theopen-source-trials-hanging-in-the-legal-balance-of-copyright-and-copyleft/


### global trade agreements

Berne convention
TRIPS
http://en.wikipedia.org/wiki/Agreement_on_Trade-Related_Aspects_of_Intellectual_Property_Rights

### Software Copyright and Copyright Infringement

Proprietary software & free and open source licenses rely on it.

Case law exists, bit within EU and US … everything is still in the flow… less FUD though!

http://en.wikipedia.org/wiki/Software_copyright

**Copyright Infringement**

Using copyrighted works without permission from the copyright holder, or not following their terms and conditions.

“Certain free software licenses, most notably GNU General Public License (GPL) substantially rely on existing copyright law. It is not possible to enforce GPL other than within the framework of existing copyright law.”
http://en.wikipedia.org/wiki/Copyright_infringement 

copyright goes two ways

“Nearly every free software project includes two types of legal information with its source code: the license(s) of the code and the copyright notices of contributing authors.”
http://www.softwarefreedom.org/resources/2012/ManagingCopyrightInformation.html

Got to understand license compatibility

Must include licenses of used software

If I create changed versions I must make sure all previous versions adhered to the license. 

http://www.estrategy-magazin.de/open-source-software-rechtliche-hintergruende-sowie-chancen-und-risiken-fuer-unternehmen.html

Distributed VCS work better in tracing contributions



## License Types

copyright vs. copyleft, strong, weak, public domain

creative commons

https://tldrlegal.com/



## Popular Licenses

popular = people actually like and dislike licenses!

* MIT License (MIT) and BSD
  * http://en.wikipedia.org/wiki/MIT_License respectively http://en.wikipedia.org/wiki/BSD_licenses 
  * Non-copyleft, permissive
* Apache Software License (ASL)
  * Apache Software License, http://www.apache.org/ 
  * Non-copyleft, permissive
* GNU General Public License (GPL), strong copyleft
* LGPL > GNU Lesser General Public License, freedom is “less” guaranteed > http://en.wikipedia.org/wiki/LGPL 
  * Weak copyleft
* Affero General Public License (AGPL) http://www.gnu.org/licenses/why-affero-gpl.en.html
  * avoding the “ASP loophole” for web services > http://en.wikipedia.org/wiki/Affero_General_Public_License 
  * Strong copyleft


All of these are licenses for software code, and **NOT** for
* creative work or art,
* licenses for open data, or
* licenses for open hardware.


## Contributor License Agreements

why, what for, how?

(links in Email auf 52N Staff discussion)

Individuals or companies don’t want to sign over IPRs (which we automatically have, see previous slides). But some control is required for long-term license management!
Solution: define all terms under which intellectual property is contributed > relicensing, handle legal disputes.

Examples:
Apache: http://www.apache.org/licenses/#clas
52°North: http://52north.org/about/licensing/contributors-license-agreement-faq 

Resources: http://www.oss-watch.ac.uk/resources/cla http://en.wikipedia.org/wiki/Contributor_License_Agreement 
http://development.contributoragreements.org/ 

https://wiki.eclipse.org/CLA

## Notices and License Headers

Notices are not required to secure copyright.

*<i class="octicon octicon-quote"></i> Contrary to popular belief, copyright notices aren’t required to secure copyright. Each developer holds copyright in his or her code the moment it is written, and because all the world’s major copyright systems—including the US after 1976—do not require notices, publishing code without a copyright notice doesn’t change this. However, notices do have some legal effect. For example, someone who infringes the copyright of a program published without a notice may be able to claim that the infringement was “innocent” because he or she had no notice of the developers’ copyright claim, and thus seek reduced damages.*
http://softwarefreedom.org/resources/2012/ManagingCopyrightInformation.html 

## IPR, Licensing and Patents

http://oss-watch.ac.uk/resources/ipr

## Version Control System

Strict requirement for copyright management, see http://www.softwarefreedom.org/resources/2012/ManagingCopyrightInformation.html#fn2 

## Trademarking

very common (e.g. Eclipse, Apache) and encouraged way to maintain control over a project


<!-- not yet sure where these could go:

http://www.linux.com/news/featured-blogs/205-mike-dolan/833369-why-companies-that-use-open-source-need-a-compliance-program

http://www.linux.com/news/featured-blogs/205-mike-dolan/833808-5-essential-duties-of-legal-counsel-in-an-open-source-compliance-program

http://www.linux.com/news/featured-blogs/205-mike-dolan/833810-5-practical-ways-for-legal-counsel-to-advise-developers-on-open-source

-->



