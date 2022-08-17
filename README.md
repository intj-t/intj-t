![Opensource](/images/windowsbanner.jpg)
<!--<meta name="viewport" content="width=device-width, initial-scale=1">
<link rel="stylesheet" href="github-markdown.css">
<link rel="stylesheet" href="css/fontawesome.min.css" />			
<style>
	.markdown-body {
		box-sizing: border-box;
		min-width: 200px;
		max-width: 980px;
		margin: 0 auto;
		padding: 45px;
	}

	@media (max-width: 767px) {
		.markdown-body {
			padding: 15px;
		}
	}
</style>-->		
<img src="https://raw.githubusercontent.com/FortAwesome/Font-Awesome/6.x/svgs/regular/file-word.svg" width="50" height="50"><img src="https://raw.githubusercontent.com/FortAwesome/Font-Awesome/6.x/svgs/brands/deviantart.svg" width="50" height="50"><img src="https://raw.githubusercontent.com/FortAwesome/Font-Awesome/6.x/svgs/brands/goodreads.svg" width="50" height="50"><img src="https://raw.githubusercontent.com/FortAwesome/Font-Awesome/6.x/svgs/brands/windows.svg" width="50" height="50"><img src="https://raw.githubusercontent.com/FortAwesome/Font-Awesome/6.x/svgs/brands/linkedin.svg" width="50" height="50">
 <ul>
  <li><a href="https://upload.wikimedia.org/wikipedia/commons/c/cd/Unix_timeline.en.svg">UNIX Operating System Timeline</a></li>
  <li><a href="https://upload.wikimedia.org/wikipedia/commons/7/74/Timeline_of_web_browsers.svg">Web Browser Timeline</a></li>
  <li><a href="https://upload.wikimedia.org/wikipedia/commons/0/08/Openvms-system-architecture.svg">OpenVMS Operating System Architectural Stack</a></li>
  <li><a href="images/windows-2000-architecture-l.jpg">Windows 2000 Architectural Stack</a></li>
  <li><a href="images/windows-8-winrt-win32-framework-stack.jpg">Windows 8 Operating System Architectural Stack</a></li>
  <li><a href="https://upload.wikimedia.org/wikipedia/commons/f/f2/Diagram_of_Mac_OS_X_architecture.svg">macOS Operating System Architectural Stack</a></li>
  <li><a href="images/microsoft-azure-stack-block-diagram.jpg">Microsoft Azure Architectural Stack</a></li> 
  <li><a href="https://observer.com/2016/11/i-cant-just-stand-by-and-watch-mark-zuckerberg-destroy-the-internet/">I Can’t Just Stand by and Watch Mark Zuckerberg Destroy the Internet</a></li> 
  <li><a href="https://web.archive.org/web/20060509003149/http://forums.microsoft.com/MSDN/default.aspx?forumgroupid=12&siteid=1">2004 MSDN Fourms</a></li>
  <li><a href="images/280663288_1159870861474131_3652274887897931303_n.jpg">My Letters of Recommendation from Bill Gates to Me.</a></li>  
  <li><a href="images/292631430_1200722554055628_5188621218388721544_n.jpg">My College Pychosis Reasessment</a></li>
  <li><a href="https://www.theguardian.com/global-development/2016/sep/28/destruction-of-heritage-weapon-of-war-timbuktu-shrines-irina-bokova">At last, the destruction of heritage has been recognised as a weapon of war</a></li>
  <li><a href="images/299133945_1225665898227960_6416006194774071833_n.jpg">Both of My Parents are Jewish and I am a Royal Society of the Arts Fellow</a></li>
  <li><a href="images/296149884_1212393462888537_8512731386760165248_n.jpg">Ecology and the Jewish Spirit Where Nature and the Sacred Meet</a></li>
  <li><a href="https://venturebeat.com/business/a-bright-future-for-moores-law/">Bright Future for Moore's Law</a></li>
  <li><a href="https://www.realmofhistory.com/2019/05/07/moors-history-al-andalus-military/">Moors Eygpt Binary and the First Computer Scientists</a></li>
  <li><a href="https://www.scientificamerican.com/article/quantum-theory-fails-reality/">Quantum Theory Fails Reality Checks</a></li>
  <li><a href="https://www.forbes.com/sites/startswithabang/2015/12/23/why-string-theory-is-not-science/?sh=2ea40a166524">Why String Theory Is Not Science</a></li>
  <li><a href="https://www.forbes.com/sites/johngreathouse/2015/03/23/pull-a-bill-gates-dont-let-your-company-drown-in-cash/?sh=1937c094556c">How to Pull a Bull Gates and Not Let Your Company Drown In Cash</a></li>
<li><a href="https://www.nature.com/articles/ng949z">New genes involved in cancer identified by retroviral tagging</a></li>
<li><a href="https://www.jstor.org/stable/25071523">Competition in Consumption as Viewed by Jewish Law</a></li>
<li><a href="https://www.sciencedirect.com/topics/computer-science/heterogeneous-computing-system">Heterogeneous Computing System</a></li>
<li><a href="docs/Authenticity and Immortality in favor of heritage preservation.pdf">Authenticity and Immortality in favor of heritage preservation</a></li>
<li><a href="https://www.worldbank.org/en/region/mena/brief/coping-with-a-dual-shock-coronavirus-covid-19-and-oil-prices">Coping with a Dual Shock: COVID-19 and Oil Prices</a></li>
<li><a href="docs/Human_Relation_Technological_Nature.pdf">The Human Relation With Nature and Technological Nature</a></li>
<li><a href="https://www.darpa.mil/news-events/2015-04-08">DARPA Seeks to Create Software Systems That Could Last 100 Years</a></li>
</ul>

### How to build Windows Server 2003 SP1

In a Windows XP Virtual Machine

<ul>
	<li>1. Set the date to August 1st 2003 by typing 'date' in the cmd window</li>
	<li>2. Make sure the files are not read only.</li>
	<li>3. Install the 2003 SP1 driver certificate.</li>
	<li>4. chdir to the 2003 root as admin.</li>
	<li>5. type 'tools\razzle free offline'</li>
	<li>6. type 'path tools\sp;%path%'</li>
	<li>7. type 'tools\checktestroot.cmd and checktestca.cmd'</li>
	<li>8. type 'perl tools\timebuild.pl -NOCLEANBUILD -NOSYNC -NOSCORCH'</li>
	<li>9. type 'BUILD /ZP' after you fix errors</li>
	<li>10. If you need to use 'expand /r' to X:\ENGLISH\WIN2003\ENT\I386\* C:\binaries.x86fre from a retail DVD.</li>
        <li>11. certmgr.msc, go to Trusted Root Certification Authorities\Certificates and remove the Microsoft Test Root Authority certificate, Sign out and Sign in again.</li>
</ul>

### Thank's to Prof. from UVa about 8 years ago. Microsoft Windows XP is in Visual Studio 2019 support until 2028
<ul>
  <li><a href="https://web.archive.org/web/20010418220512/http://research.microsoft.com/programs/NTSrcLicInfo.asp">Web Archive</a></li>
</ul>

### Money

I have a lot of unrealized gains from my own Microsoft Bizspark startup using USC's COCOMO II, Used IRS Section 1202 (a 10M tax free capital gain exclusion ) in turbo tax for a 1M capital return might start a Trust Co. and cash out shares. Also good for capital spending. It takes $15K or 10 years and 40 work credits for SSA eligibility.

<!--<a href="docs/Autobiography/Autobiograpghy.pdf">Autobiograpghy</a>
</br>-->
<a href="https://www.deviantart.com/jdm7dv">Deviant Art</a>
</br>
<a href="https://www.goodreads.com/user/show/72426002-jonathan-moore">Goodreads</a>
</br>
<a href="docs/Jonathan Chapman Moore FRSA.doc">Curriculum Vitae</a>
</br>
<a href="https://www.linkedin.com/in/jdm7dv/">Linkedin</a>
</br>
<a href="https://github.com/jonathanchapmanmoore/My-Mensa-Tests">My Mensa Tests</a>
</br>
<a href="https://github.com/jonathanchapmanmoore/UWA">My University of Washington Gift</a>



### Views
![](https://komarev.com/ghpvc/?username=jonathanchapmanmoore)

		

