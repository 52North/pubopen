<div class="panel panel-info">
    <div class="panel-heading">
        <h3 class="panel-title"><i class="octicon octicon-megaphone"></i> Guide: What license should I use for my software project?</h3>
    </div>
    <div class="panel-body">
        <p>First of all, congratulations! You have realized that <b>no license does not make your project usable by others</b>, because your legal systems probably gives you rights about your work whether you want them or not. If you did not know that, read the <a href="http://www.gnu.org/licenses/license-list.html#NoLicense">entry about "No license" in the FSF license list</a> and this interesting <a href="http://www.theregister.co.uk/2013/04/18/github_licensing_study">study about licenses on GitHub</a>.
        </p>
        
        <p>As for choosing a license, you have the agony of choice. However, people realize that the open source license world can be complex to understand, and we strongly recommend to go with one of the most used and established licenses. These were divided into thread broad categories and briefly explained by the GitHub folks on the website <a href="http://choosealicense.com/">choosealicense.com</a>. Thanks to this page, choosing a license becomes a two-minute-task. They don't suggest any license in parcticular and even explain the <a href="http://choosealicense.com/no-license/">"no license" option</a>.</p>
        
        <p>Based on <em>our experiences</em>, we recommend the Apache License if it is possible, because it a bit closer to the real world compared to the "short" licenses (MIT, BSD), taking into considereation that the world is a bad place with software patents, but also allows any commercial application to integrate and extend a software project.</p>
        
        <p>Besides your own ideas, third-party libraries, i.e. software that you use or extend, are an important impact on choosing a license.</p>
        
        <p>The minimal steps to of choosing a license for software out of a research project would be as follows.</p>
        <ol>
            <li>Create a comprehensive lists of software that you strictly rely on or directly extend, and their licenses. These are your "third-party licenses".
            <li>Go to <a href="http://choosealicense.com/">choosealicense.com</a> and pick a license that fits your goals.</li>
            <li>Check all third-party licenses for compatibility with your chosen license.</br>
            This requires some searching on the web and potentially involving a lawyer specializing in open source if the licenses of your dependencies are not the typical ones. Sadly, we are not laywers and cannot make clear recommendations for you here. As a guideline, you may check the following websites, but you must judge yourself if these recommendations apply to you. We do _not_ want to scare you! In 90% of the cases the answer is very straightforward, but due diligence is required.</li>
                <ul>
                    <li><a href="https://en.wikipedia.org/wiki/Comparison_of_free_and_open-source_software_licenses">"Comparison of free and open-source software licenses" on Wikipedia</a></li>
                    <li><a href="http://oss-watch.ac.uk/apps/licdiff/">OSSWATCH licence differentiator</a></li>
                    <li></li>
                    <li></li>
                    
                    <li><a href="https://wiki.52north.org/bin/view/Documentation/LicenseManagement">52°North's list of third-party components</a></li>
                    <li></li>
                </ul>
            <li>Check with <em>all</em> contributors of the software if they are OK with your publishing the license.</li>
            <li>Check with guidelines or agreements that are part of the funding you conducted the development with, e.g. research grants.</li>
            <li>Revise your decision if any of 3. to 5. result in issues. If choosealicense.com is not detailed enough for you, answer seven questions in the <a href="http://oss-watch.ac.uk/apps/licdiff/">OSSWATCH licence differentiator</a> to get a more detailed choice.</li>
            <li>Done.</li>
        </ol>
    </div>
    <div class="panel-footer">
        <i class="octicon octicon-link-external"></i> For more extensive lists of open source licenses, please see the list of <a href="http://opensource.org/licenses">OSI-approved licenses</a> and the <a href="http://www.gnu.org/licenses/license-list.html">license list by the FSF</a>.
        The latter also as very short human readable summaries and recommendations yet focusses on the FSF's perspective.
    </div>
</div>

