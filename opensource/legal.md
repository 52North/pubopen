# Legal Stuff

["IANAL"](https://en.wikipedia.org/wiki/IANAL) - I am not a lawyer. We have some experience with open sources licensing, but we cannot give you the professional advice that your require. There are many different legal systems in the world. If you are in doubt about legal matters regarding your open source software or software that you use, then [get a lawyer or get in touch with colleagues and your legal department](http://www.linux.com/news/featured-blogs/205-mike-dolan/833808-5-essential-duties-of-legal-counsel-in-an-open-source-compliance-program).

There is, however, a plethora of guides and opinions available online and in books. In this section, we introduce some basic information and try to summarize the matter for the most typical scenarios.


## Basics

### Copyright

&copy;

[Copyright](http://en.wikipedia.org/wiki/Copyright) is a legal concept that gives the creator of a work certain rights to (exclusively) use that work, grant permissions to other persons, etc. It is intended to protect the creator(s) from economical and ideological abuse of their works. You, as a creator, have the copyright by default and usually you can determine under which conditions your work may be used by others. However, the exact scope depends on the specific applicable law (e.g. the copyright laws of specific countries).

Please note that there are also limitations regarding the copyright, which grant some exceptions for specific cases. This is referred to as “fair use”. We recommend reading this [Wikipedia article](https://en.wikipedia.org/wiki/Fair_use). Other limitations concern the copyright's expiration after certain periods (depending on the specific laws).

Copyright requires that the work you created has a certain threshold of originality. This threshold is generally rather low. An interesting discussion about this topic can be found [here](http://softwarefreedom.org/resources/2007/originality-requirements.html).

[History](http://en.wikipedia.org/wiki/History_of_copyright_law): In the old Roman Empire and the medieval ages, there was no copyright. At that time, it was extremely laborious to copy a text, so this was not really an issue. However, this changed with the invention of the letterpress and led to the “Printer’s Privilige” Act of 1709, also known as the Statute of Anne (British law). Other examples include the Droit d’auteur (France, 1793: authors wanted acknowledgment not money) or the German Urheberrechtsgesetz (UrhG) from 1965. 

### Copyleft

<img src="https://upload.wikimedia.org/wikipedia/commons/8/8b/Copyleft.svg" width="48">

If your work is free, you might also want that any modification or extensions of this work be free. This concept is called “copyleft”.  Copyleft ensures that your software is free and that all modifications and extensions of your code have to be free too. [GNU](http://www.gnu.org/copyleft/copyleft.html) explains this as follows:

*"Proprietary software developers use copyright to take away the users' freedom; we use copyright to guarantee their freedom. That's why we reverse the name, changing 'copyright' into 'copyleft.'”*

We distinguish between different types of copyleft. Generally, there are three main categories:
* Strong copyleft requires all derived work to inherit the original copyleft license
* Weak copyleft refers to licenses, which do not require that all derived work inherit the copyleft license. For example, you may link your software to a weak copyleft licensed library without using the same license. However, if you change the original software, the copyleft license needs to be kept. This is useful, for example, if you want to publish libraries that should be re-usable by a broad range of other projects.
* Non-copyleft does not have requirements on the license of derived software.

As you will see later on, the different types of copyleft are an important factor when choosing an open source license for your software.


Recommended reading:
* http://www.gnu.org/copyleft/
* http://en.wikipedia.org/wiki/Copyleft
* http://www.visionmobile.com/blog/2011/03/theopen-source-trials-hanging-in-the-legal-balance-of-copyright-and-copyleft/


### Global Trade Agreements

International conventions regulate how to handle copyright between different countries. An important element is the [Berne convention](http://en.wikipedia.org/wiki/Agreement_on_Trade-Related_Aspects_of_Intellectual_Property_Rights).


### Software Copyright and Copyright Infringement

All software, proprietary and free and open source, relies on copyright. Although copyright in and of itself has a long history, its application to the specifics of software is still in the making. In the EU and USA, there is mainly Case Law on this topic. The concept of copyright lays the foundation for the conditions of open source licenses.

Recommended Reading:
* [Software Copyright](http://en.wikipedia.org/wiki/Software_copyright)

**Copyright Infringement**

If you are using copyrighted works without permission from the copyright holder, or if you do not follow their terms and conditions, this is called [copyright infringement](http://en.wikipedia.org/wiki/Copyright_infringement). This could have serious legal consequences. In order to avoid copyright infringements, you should consider several aspects:

* When you use open source code, look for two types of legal information 1) the license(s) of the code and 2) the copyright notices of contributing authors (see also [Managing Copyright Information](http://www.softwarefreedom.org/resources/2012/ManagingCopyrightInformation.html)). 

* Make sure you understand the compatibility of the license(s) of this code with the license you are using for your own code (and with the licenses of other components you are using).

* When you publish your code under an open source license, you are required not only to provide information about the license you are using yourself, but also about the licenses of all libraries/software that you are using in your source code. There are efficient tools and mechanisms that help you trace contributions and licenses of any third party code in many distributed version control systems.


## License Types

In addition to the copyleft licenses "strong copyleft", "weak copyleft" and "non-copyleft" mentioned above, there is a specific category known as "public domain”. This covers works for which the intellectual property rights have expired or have been forfeited. Other types of licenses, such as Creative Commons, are not really intended for software. They do not contain any provisions for the distribution of source code. It is NOT recommended to use Creative Commons licenses for software. 


## Popular Licenses

Open source projects tend to favor certain licenses over others. The following overview shows some of the most commonly used open source software licenses: 
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

See [explanations of the different licenses for software code](https://tldrlegal.com/). 

Other types of licenses, would be better suited for works other than software code.  
* Creative work or art: Licenses such as Creative Commons
* Open data: Licenses such as Open Data Commons (ODC)
* Open hardware: Many projects use licenses inspired by open source software licenses but with important differences (see also [Open Source Hardware](https://en.wikipedia.org/wiki/Open-source_hardware)).


## Contributor License Agreements

If you want to contribute to an open source project, you are often required to sign a so-called contributor license agreement (CLA). The signed CLA enables the legal body behind an open source project
* to work with your code contribution (e.g. to reproduce, to modify, to create derivative works and to combine the contribution with other software code)
* to grant the Open Source License to potential users
* to change the terms of the Open Source License for a particular software project if necessary (e.g. changing from a strong copyleft license to a weak copyleft license)
* to handle legal disputes.

The CLA does NOT require you to transfer the full intellectual property rights (IRP) associated with your copyright (in some countries this is legally impossible and, from a company viewpoint, it is often undesirable). Instead, you transfer only those rights necessary to allow the long-term license management of the project to which you are contributing.
The following example of CLAs give you an impression of how they work:
* Apache: http://www.apache.org/licenses/#clas 
* 52°North: http://52north.org/about/licensing/contributors-licenseagreement-faq

Recommended readings:
* http://www.oss-watch.ac.uk/resources/cla
* http://en.wikipedia.org/wiki/Contributor_License_Agreement
* http://development.contributoragreements.org/
* https://wiki.eclipse.org/CLA


## Notices and License Headers

Copyright notices and license headers are not required to secure copyright. Based on most national laws, the creator of a work automatically holds the copyright the moment the work is created (e.g. if you have written a line of code). However, this does NOT mean that you should not provide copyright notices and license headers as they have certain legal implications.
* If someone infringes your copyright and there are no copyright notices/license headers, he might use this as an argument to reduce your claims.
* The license header makes it easy to immediately determine the author and license of a certain piece of source code.
* You improve your visibility as the author of a certain piece of source code.

You can find more information on this topic [here](http://softwarefreedom.org/resources/2012/ManagingCopyrightInformation.html).


## Trademarking

Many open source projects (e.g. Eclipse, Apache) rely on trademarking to maintain control ofa project's identity. You can control better who is using your logo or name and in what context if you have registered corresponding trademarks. As you can imagine, this can become a serious issue.

Recommended Reading:
* http://communityovercode.com/2011/01/trademarks-in-open-source/
* http://www.ifosslr.org/ifosslr/article/view/11


## Further Resources

The UK-based organization OSS watch is a great resource addressing many aspects of this chapter: **http://oss-watch.ac.uk/resources/ipr**


<!-- not yet sure where these could go:

http://www.linux.com/news/featured-blogs/205-mike-dolan/833369-why-companies-that-use-open-source-need-a-compliance-program

http://www.linux.com/news/featured-blogs/205-mike-dolan/833810-5-practical-ways-for-legal-counsel-to-advise-developers-on-open-source

-->



