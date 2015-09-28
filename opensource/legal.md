# Legal Stuff

["IANAL"](https://en.wikipedia.org/wiki/IANAL) - I am not a lawyer. We have some experience with open sources licensing, but we cannot give you the professional advice that your require. There are many different legal systems in the world. If you are in doubt about legal matters regarding your open source software or software that you use, then [get a lawyer or get in touch with colleagues and your legal department](http://www.linux.com/news/featured-blogs/205-mike-dolan/833808-5-essential-duties-of-legal-counsel-in-an-open-source-compliance-program).

There is, however, a plethora of guides and opinions available online and in books. We introduce some basic information and try to summarize the matter for the most typical scenarios.


## Basics

### Copyright

&copy;

[Copyright](http://en.wikipedia.org/wiki/Copyright) is a legal concept that gives the creator of a work certain rights to (exclusively) use that work, grant permissions to other persons, etc. It is intended to protect the creator(s) from economical and ideological abuse of their works. You, as a creator have the copyright by default and usually you can determine under which conditions your work may be used by others. However, the exact scope, which rights a creator of a work has, depends on the specific applicable law (e.g. the copyright laws of specific countries).

Please note that there are also limitations regarding the copyright, which grant some exceptions for specific cases. This is referred as “fair use”. To get an overview, we recommend this [Wikipedia article](https://en.wikipedia.org/wiki/Fair_use). Other limitations concern the exhaustion of the copyright after certain periods (depending on the specific laws).

Finally, copyright requires that you have created some work that has a certain threshold of originality. However, this threshold is generally rather low. An interesting discussion about this topic can be found [here](http://softwarefreedom.org/resources/2007/originality-requirements.html).

Finally, some history: In the old Roman Empire and the mediaeval ages, there was no copyright. At that time it took extremely high efforts to copy a text so that this was not really an issue. However, with the invention of the letterpress this changed. For example this has led to the “Printer’s Privilige” Act of 1709, also known as the Statute of Anne (British law). Other examples are the Droit d’auteur (France, 1793: authors want acknowledgement not money) or the German Urheberrechtsgesetz (UrhG) from 1965. You can find a detailed overview on the history of the copyright on [Wikipedia](http://en.wikipedia.org/wiki/History_of_copyright_law).


### Copyleft

<img src="https://upload.wikimedia.org/wikipedia/commons/8/8b/Copyleft.svg" width="48">

If you want to make your work free, you might also want that any modification or extensions of this work shall be free. This concept is also called “copyleft”.  This means that you can use the copyleft as a method to ensure that your software is free and that all modifications and extensions of your code have to be free, too. GNU explains this as follows  (http://www.gnu.org/copyleft/copyleft.html):

*"Proprietary software developers use copyright to take away the users' freedom; we use copyright to guarantee their freedom. That's why we reverse the name, changing 'copyright' into 'copyleft.'”*

When talking about copyleft, we need to distinguish different types of copyleft. Generally, we can see three main categories:
* Strong copyleft requires all derived work to inherit the original copyleft license
* Weak copyleft refers to licenses, which do require not for all derived work that it inherits the copyleft license. For example, you may link your software to a weak copyleft licensed library without using the same license. But if you change the original software, the copyleft license needs to be kept. This is for example useful if you want to publish libraries that shall be re-usable by a broad range of other projects.
* Non-copyleft does not have requirements on the license of derived software.
As you will see later on, the different types of copyleft are an important factor when choosing an open source license for your software.

If you would like to learn more about copyleft, we recommend the following resources:
* http://www.gnu.org/copyleft/
* http://en.wikipedia.org/wiki/Copyleft
* http://www.visionmobile.com/blog/2011/03/theopen-source-trials-hanging-in-the-legal-balance-of-copyright-and-copyleft/


### Global Trade Agreements

As the copyright laws are very heterogeneous across the world, it is necessary to have international conventions in place to regulate the handling of copyright between different countries. An important element in this context is the [Berne convention](http://en.wikipedia.org/wiki/Agreement_on_Trade-Related_Aspects_of_Intellectual_Property_Rights).


### Software Copyright and Copyright Infringement

In the previous paragraphs, we often used the term “copyright” in conjunction with the more abstract concept “work”. In this book, we deal with a specific type of work: software and source code. Thus, we need to apply the different rules of copyright, copyleft, licenses, etc. on software. Every software, proprietary as well as free and open source software, relies on copyright. While the general concept of copyright has a long history, its application to the specifics of software is still in the flow. In the EU and as well as in the US there is mainly case law on this topic. However, without the concept of copyright it would not be possible the conditions of open source licenses.

For a more detailed overview, we recommend this article: http://en.wikipedia.org/wiki/Software_copyright

**Copyright Infringement**

As you have read, there are many licenses with different conditions. If you are using copyrighted works without permission from the copyright holder, or if you do not follow their terms and conditions, this is called [copyright infringement](http://en.wikipedia.org/wiki/Copyright_infringement). In order to avoid copyright infringements, which may have serious legal consequences, you should consider several aspects:

When you want to use open source code, there are two types of legal information that you should look for: the license(s) of the code and the copyright notices of contributing authors (see also  http://www.softwarefreedom.org/resources/2012/ManagingCopyrightInformation.html). 

Based on this analysis you should be able to understand the compatibility of the license(s) of this code with the license you are using for your own code (and with the licenses of other components you are using).

Furthermore, when you publish your code under an open source license, you are required not only to provide information about the license you are using yourself, but also about the licenses of all libraries/software that you are using from your source code.

In many distributed version control system you also receive efficient tools and mechanisms that help you to trace contributions and the licenses of any third party code that is used.


## License Types

Previously we have already shortly discussed the classification of licenses based on their copyleft. With the additional, specific category, “public domain” this leads to the following groups of open source licenses:
* Strong copyleft requires all derived work to inherit the original copyleft license
* Weak copyleft refers to licenses, which do require not for all derived work that it inherits the copyleft license. For example, you may link your software to a weak copyleft licensed library without using the same license. However, if you change the original software, the copyleft license needs to be kept. This is for example useful if you want to publish libraries that shall be re-usable by a broad range of other projects.
* Non-copyleft does not have requirements on the license of derived software.
* Public domain: These are works where the intellectual property rights have expired or have been forfeited

Besides this, there are other types of licenses such as Creative Commons. However, these licenses are not really intended for software (for example they do not contain any provisions about the distribution of source code). Typically, Creative Commons might be used for works such as photographs, videos, texts, music, etc. Thus, it is not recommended to use Creative Commons licenses for software. 


## Popular Licenses

If you analyze the licenses used by open source software projects, you will note that certain licenses are used more often than other licenses. You can observe that people sometimes like or dislike certain licenses. The following overview shows some of the most commonly used open source software licenses: 
* MIT License (MIT) and BSD
 * Non-copyleft licenses
 * Very permissive
 * http://en.wikipedia.org/wiki/MIT_License and http://en.wikipedia.org/wiki/BSD_licenses
* Apache Software License (ASL)
 * Non-copyleft
 * Permissive
 * http://www.apache.org/
* GNU General Public License (GPL)
 * Strong copyleft
 * http://www.gnu.org/licenses/
* GNU Lesser General Public License (LGPL)
 * Weak copyleft
 * http://en.wikipedia.org/wiki/LGPL
 * http://www.gnu.org/licenses/
* Affero General Public License (AGPL)
 * Strong copyleft
 * Closes a loophole that mainly applies to software deployed on Web servers (see http://www.gnu.org/licenses/why-affero-gpl.en.html)
 * http://www.gnu.org/licenses/

If you would like to have nice explanations of the different licenses, you might have a look at https://tldrlegal.com/. You can also use this as an overview about further licenses beyond this list.

Please note: All of these are licenses for software code. For other works other licenses would be better suited:
* Creative work or art: Licenses such as Creative Commons
* Open data: Licenses such as Open Data Commons (ODC)
* Open hardware: Many projects use licenses inspired by open source software licenses but with important differences (see also https://en.wikipedia.org/wiki/Open-source_hardware) 


## Contributor License Agreements

If you want to contribute to an open source project, you are often required to sign a so-called contributor license agreement (CLA). There are several reasons for this. With a CLA you allow the legal body behind an open source project
* to work with you code contribution (e.g. to reproduce, to modify, to create derivative works and to combine the contribution with other software code)
* to grant the Open Source License to potential users
* to change the terms of the Open Source License for a particular software project if necessary (e.g. changing from a strong copyleft license to a weak copyleft license)
* to handle legal disputes

With a CLA you do not have to transfer your full intellectual property rights associated to your copyright (in some countries this is even legally impossible and from a company viewpoint this is often not desirable). Instead, you transfer only those rights that are necessary to allow the long-term license management of the project to which you are contributing.
There are some example of CLAs which you might study to get a better impression how they work:
* Apache: http://www.apache.org/licenses/#clas 
* 52°North: http://52north.org/about/licensing/contributors-licenseagreement-faq

Further recommended readings are:
* http://www.oss-watch.ac.uk/resources/cla
* http://en.wikipedia.org/wiki/Contributor_License_Agreement
* http://development.contributoragreements.org/
* https://wiki.eclipse.org/CLA


## Notices and License Headers

Copyright notices and license headers are not required to secure copyright. Based on most national laws, the creator of a work automatically hold the copyright with the moment it is created (e.g. if you have written a line of code). 
However, this does not mean that you should not provide copyright notices and license headers as they have certain legal implications:
* If someone infringes your copyright and there are no copyright notices/license headers, he might use this as an argument to reduce your claims.
* The license header makes it easy to determine immediately the author and license of a certain piece of source code.
* You improve your visibility as the author of a certain piece of source code.

You can find more information on this topic [here](http://softwarefreedom.org/resources/2012/ManagingCopyrightInformation.html).


## Trademarking

Many open source projects (e.g. Eclipse, Apache) rely on trademarking to maintain control over the identity of a project. By registering corresponding trademarks, it becomes possible for you to better control who is using your logos or name in which context. As you can imagine, this can become a serious issue.

If you would like to dive a bit deeper into this topic, you may have a look at these two resources:
* http://communityovercode.com/2011/01/trademarks-in-open-source/
* http://www.ifosslr.org/ifosslr/article/view/11


## Further Resources

The UK-based organisation OSS watch is great resources page addressing many aspects addressed in this chapter: **http://oss-watch.ac.uk/resources/ipr**


<!-- not yet sure where these could go:

http://www.linux.com/news/featured-blogs/205-mike-dolan/833369-why-companies-that-use-open-source-need-a-compliance-program

http://www.linux.com/news/featured-blogs/205-mike-dolan/833810-5-practical-ways-for-legal-counsel-to-advise-developers-on-open-source

-->



