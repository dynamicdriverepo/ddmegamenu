# DD Mega Menu #

*Description:*  DD Mega Menu is the ideal menu script to use when you need a drop down menu system that supports arbitrary sub menu layouts, such as multiple columns of links or even arbitrary HTML. Each drop down menu is simply defined inline on the page as a regular DIV, making it extremely easy to customize its contents whichever way you like.

## Directions ##

*Step 1:* This script uses the following external files:

+ jQuery 1.5 or above (served via Google CDN)
+ ddmegamenu.js
+ ddmegamenu.css

*Step 2:* Add the below code to the HEAD section of your page:

	<link rel="stylesheet" type="text/css" href="ddmegamenu.css" />
	
	<script type="text/javascript" src="http://ajax.googleapis.com/ajax/libs/jquery/1.5.2/jquery.min.js"></script>
	
	<script src="ddmegamenu.js">
	
	/***********************************************
	* DD Mega Menu (c) Dynamic Drive (www.dynamicdrive.com)
	* This notice MUST stay intact for legal use
	* Visit http://www.dynamicdrive.com/ for this script and 100s more.
	***********************************************/
	
	</script>
	
	<script>
	
	ddmegamenu.docinit({
		menuid:'solidmenu',
		dur:200 //<--no comma after last setting
	})
	
		
	ddmegamenu.docinit({
		menuid:'megaanchorlink',
		dur:500,
		easing:'easeInOutCirc' //<--no comma after last setting
	})
	
	</script>


*Step 3:* Then, add the below sample markup to your page:

	<h2>Example 1</h2>
	
	<ul id="solidmenu" class="solidblockmenu">
	<li><a href="http://www.dynamicdrive.com/">Home</a></li>
	<li><a href="http://www.javascriptkit.com" rel="jkmenu">JavaScript v</a></li>
	<li><a href="http://www.dynamicdrive.com/forums/">Forums</a></li>
	<li><a href="http://tools.dynamicdrive.com">Webmaster Tools</a></li>
	<li><a href="http://www.cssdrive.com" rel="cssdrivemenu[left]">CSS Drive v</a></li>
	</ul>
	
	<!--First mega menu (1) -->
	
	<div id="jkmenu" class="mega solidblocktheme">
	
		<p style="margin:5px 0 10px 0"><b>Visit the following main content areas of JavaScript Kit:</b></p>
	
		<div class="column">
		<ul>
		<li><a href="http://www.javascriptkit.com"  rel="freescripts">Free JavaScripts</a></li>
		<li><a href="http://www.javascriptkit.com">JavaScript Tutorials</a></li>
		<li><a href="http://www.javascriptkit.com">Free Java Applets</a></li>
		</ul>
		</div>
		<div class="column">
		<ul>
		<li><a href="http://www.javascriptkit.com">JavaScript Tutorials</a></li>
		<li><a href="http://www.javascriptkit.com">DHTML Tutorials</a></li>
		<li><a href="http://www.javascriptkit.com">Web Design Tutorials</a></li>
		</ul>
		</div>
		<br style="clear:left" />
		<p>Need help with JavaScript? <a href="http://www.codingforums.com">Coding Forums</a> should be your next stop!</p>
	
	</div>
	
	<!--Second mega menu (1.1) -->
	
	<div id="freescripts" class="mega solidblocktheme" style="width:150px">
		<ul class="ulmenu">
			<li><a href="http://www.javascriptkit.com/cutpastejava.shtml">JavaScript Clocks</a></li>
			<li><a href="http://www.javascriptkit.com/cutpastejava.shtml">JavaScript Scrollers</a></li>
			<li><a href="http://www.javascriptkit.com/cutpastejava.shtml">Text Effects</a></li>
			<li><a href="http://www.javascriptkit.com/cutpastejava.shtml">Password Protecting</a></li>
			<li><a href="http://www.javascriptkit.com/cutpastejava.shtml">Form Validation</a></li>
			<li><a href="http://www.javascriptkit.com/cutpastejava.shtml">Ajax Scripts</a></li>
			<li><a href="http://www.javascriptkit.com/cutpastejava.shtml">Image Effects</a></li>
			<li><a href="http://www.javascriptkit.com/cutpastejava.shtml">Link Effects</a></li>
		</ul>
	</div>
	
	
	<!--Forth mega menu (2) -->
	
	<div id="cssdrivemenu" class="mega solidblocktheme">
	
	<p style="margin-top:10px">Looking for web design inspiration? CSS Drive showcases some of the most attractive, CSS driven sites on the net.</p>
	
		<div class="column">
		<ul>
		<li><a href="http://www.cssdrive.com/">Gallery</a></li>
		<li><a href="http://www.cssdrive.com/">CSS Menus</a></li>
		<li><a href="http://www.cssdrive.com/">CSS Examples</a></li>
		</ul>
		</div>
		<div class="column">
		<ul>
		<li><a href="http://www.cssdrive.com/">Design News</a></li>
		<li><a href="http://www.cssdrive.com/">Design Resources</a></li>
		<li><a href="http://www.cssdrive.com/">Design Tools</a></li>
		</ul>
		</div>
	
	</div>
	
	<br />
	
	
	
	
	
	
	
	
	
	
	
	
	<h2>Example 2</h2>
	
	
	
	<a id="megaanchorlink" href="http://www.javascriptkit.com" rel="megacontent">JavaScript Kit</a>
	
	<!--First mega menu (1) -->
	
	<div id="megacontent" class="mega">
	
		<p style="margin:5px 0 10px 0"><b>Visit the following main content areas of JavaScript Kit:</b></p>
	
		<div class="column">
		<ul>
		<li><a href="http://www.javascriptkit.com"  rel="megasubcontent">Free JavaScripts</a></li>
		<li><a href="http://www.javascriptkit.com">JavaScript Tutorials</a></li>
		<li><a href="http://www.javascriptkit.com">Free Java Applets</a></li>
		</ul>
		</div>
		<div class="column">
		<ul>
		<li><a href="http://www.javascriptkit.com">JavaScript Tutorials</a></li>
		<li><a href="http://www.javascriptkit.com">DHTML Tutorials</a></li>
		<li><a href="http://www.javascriptkit.com">Web Design Tutorials</a></li>
		</ul>
		</div>
		<br style="clear:left" />
		<p>Need help with JavaScript? <a href="http://www.codingforums.com">Coding Forums</a> should be your next stop!</p>
	
	</div>
	
	<!--Second mega menu (1.1) -->
	
	<div id="megasubcontent" class="mega" style="width:150px">
		<ul class="ulmenu">
			<li><a href="http://www.javascriptkit.com/cutpastejava.shtml">JavaScript Clocks</a></li>
			<li><a href="http://www.javascriptkit.com/cutpastejava.shtml">JavaScript Scrollers</a></li>
			<li><a href="http://www.javascriptkit.com/cutpastejava.shtml">Text Effects</a></li>
			<li><a href="http://www.javascriptkit.com/cutpastejava.shtml">Password Protecting</a></li>
			<li><a href="http://www.javascriptkit.com/cutpastejava.shtml">Form Validation</a></li>
			<li><a href="http://www.javascriptkit.com/cutpastejava.shtml">Ajax Scripts</a></li>
			<li><a href="http://www.javascriptkit.com/cutpastejava.shtml">Image Effects</a></li>
			<li><a href="http://www.javascriptkit.com/cutpastejava.shtml">Link Effects</a></li>
		</ul>
	</div>

## DD ScrollSpy Menu set up ##

See script project page for additional details on setup and documentation: <http://www.dynamicdrive.com/dynamicindex1/ddmegamenu.htm>
