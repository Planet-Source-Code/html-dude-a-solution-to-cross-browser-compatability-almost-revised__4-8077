<div align="center">

## A solution to cross browser compatability \(Almost\) \*REVISED\*


</div>

### Description

Script written for IE doesn't display correctly in wetscape, or vice versa. Here is a possible solution to your scripting compatablity problems.
 
### More Info
 


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[HTML Dude](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/html-dude.md)
**Level**          |Beginner
**User Rating**    |3.4 (17 globes from 5 users)
**Compatibility**  |ASP \(Active Server Pages\), HTML, VbScript \(browser/client side\)

**Category**       |[Internet/ Browsers/ HTML](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/internet-browsers-html__4-9.md)
**World**          |[ASP / VbScript](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/asp-vbscript.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/html-dude-a-solution-to-cross-browser-compatability-almost-revised__4-8077/archive/master.zip)





### Source Code

```
<head>
<style>
p.dude {width:80%; font-family:helvetica; font-size:85%;margin-left: 20px}
h3.dude01 {font-family:helvetica; font-size:90%;font-weight:500px;margin-left: 10px}
ol.dude02 {font-family:helvetica; font-size:80%;font-weight:500px;margin-left: 50px}
pre.dude03 {font-family:helvetica; font-size:83%;margin-left: 30px}
</style>
</head>
<h2>A solution to cross browser compatability (Almost)</h2>
<p class="dude">
Many of us who in the past have taught ourselves to script using any of the markup languages, HTML, CSS, have always been caught out by the apparent and real problems of cross browser scripting compatability.
</p>
<p class="dude">
Script written for <b>ie</b> doesn't display correctly in <b>wetscape</b>, or vice versa.
</p>
<p class="dude">
Well here is a possible solution to all your scripting compatablity problems.
</p>
<p class="dude">
This is a follow up, to the follow up, to Sam's arcticle posted 4/13/2001 11:23:48 PM, by VBguy.
</p>
<p class="dude"><a href="http://www.planet-source-code.com/vb/scripts/ShowCode.asp?txtCodeId=6592&lngWId=4">Browser Wars 2</a>
</p>
<p class="dude">
Yes I did say its a "follow up, to a follow up".
</p>
<p class="dude">
I would just like to make a few statements about the possible reasons VBguys web pages might not display in <b>wetscape</b> the same way as they do in <b>ie</b>.
</p>
<p class="dude">
Also let me state that I absolutely detest <b>wetscape</b> for the following (and I think valid) reasons.
</p>
<h3 class="dude01">Reasons To Detest <b>wetscape</b></h3>
<ol class="dude02">
	<li>
	It is an ugly and most user unfreindly GUI. (my personal opinion)</li>
	<li>
	It's now owned by AOL (Always Off Line?) a disgusting corporate bloat, which preys on the ignorance of innocents (much more so than microcrap does). AOL now owns Warners, Winamp and many other companies and products and is competing with microcrap on equal terms. they too are merciless in their quest for global dommination, maybe even more so than microcrap. (Not that I am particularly fond of microcrap and the methods it in it's quest for global domination).</li>
	<li>
	Yes, I will agree that in it's latest incarnation, it complies more closely with the W3C recommendations than <b>ie</b> does. And maybe some of the previous versions, but <b>wetscape</b> too have added their own extensions to the WC3 recommendations and it is these <b>wetscape</b> additions which cause us web creators to pull our hair out more often than not.</li>
	<li>
	It will not open pages in "full screen" mode as does <b>ie</b>.</li>
	<li>
	Its HORRIBLE and tries to take over my machine (Just like ie does)</li>
</ol>
<h3 class="dude01">Reasons why your pages might not display correctly</h3>
<p class="dude">
Now having said all that, I am afraid the real reason why your web pages do not display correctly in <b>wetscape</b> is because you are merely following
microcraps methods of writing HTML (and CSS) and not conforming to the guidelines as laid down by the W3C.
</p>
<p class="dude">
Of course this is understandable, because most of us either:
<ol type="a" class="dude02">
		<li>learned to script using one or the other flavour of <b>ie</b>.</li>
		<li>we used a wyswyg editor, conforming to either one or the other browsers scripting styles.</li>
	</ol>
<p class="dude">
Frontpage and Dreamweaver are the usual rogue suspects here methinks.
</p>
<p class="dude">
But even then with a little effort and patience, even these pages can be adjusted to display similarly in most browser.
</p>
<p class="dude">
<b>NOTE</b>
</p>
<p class="dude"><b>Newer version of frontpage and dreamweaver might create
simple pages which are cross browser compatible, but when you start creating
more complex pages, there is a higher risk of non compatibility, no matter what
their creators might say.</b>
</p>
<h3>Using DOCTYPE and DOM </h3>
<p class="dude">
The trick is to use the "DOCTYPE declaration" in all of your web documents. Using the DOCTYPE declaration, enables the browser to parse and compile your document correctly.
</p>
<p class="dude"><b>Example of a correctly declared XHTML document with an XML
declaration (XML declaration used to notify user agents that this document is
"iso-8859-1" encoded.</b>
</p>
<pre class="dude03"><?xml version="1.0" encoding="iso-8859-1"?>
<!DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.1//EN"
  "http://www.w3.org/TR/xhtml11/DTD/xhtml11.dtd">
</pre>
<p class="dude">
Unfortunately if used incorrectly, or with non conforming and invalid scripts, your pages still will look c.r.a.p, and be displayed differently by both browsers, because like the "higher" programming languages, only valid code will be interpreted correctly as each page is parsed by a browser.
</p>
<p class="dude">
For more in depth information see the following link to an excellent article on the subject of the DOM (Document Object model). I think this is essential reading for ASP coders, since it gives you a very simplified description of the concepts and uses of the DOM.
</p>
<p class="dude">
<a href="http://wsabstract.com/javatutors/dom.shtml">Introduction to the DOM
of IE 5/ NS 6</a>
</p>
<p class="dude">
 
</p>
<h3>Hurrah, A solution to cross browser compatability (Almost)</h3>
<p class="dude">
Which brings me to my main point, which is that, we are now somewhat closer to a solution which goes some way to addressing the issue of cross browser
compatibility, in that both microcrap and <b>wetscape</b> have agreed (in principle at least) to more closely conform to the W3C DOM guidelines and more especially the way their browsers will treat valid and invalid HTML, XHMTL and CSS, of any flavour (version).
</p>
<p class="dude">
Scripts conforming to valid XHMTL will be displayed almost similarly by both <b>ie</b> 6 and higher and <b>wetscape</b> 7 and higher.
</p>
<p class="dude">
See the link below to view what constitutes valid XHTML.
</p>
<p class="dude">
<a href="http://www.w3.org/TR/xhtml2/conformance.html">http://www.w3.org/TR/xhtml2/conformance.html</a>
</p>
<p class="dude">
Also take a look at the rules of conformance (link below) for USER AGENTS. This will give you an idea of how the newer browsers (user agents) will parse valid and invalid DTD's.
</p>
<p class="dude">
<a href="http://www.w3.org/TR/2001/REC-xhtml-modularization-20010410/conformance.html">XHTML Conformance</a>
</p>
<p class="dude">
Also non XHTML documents will be parsed and displayed in the same way as each previous version of a given browser would have parsed and displayed it.
</p>
<p class="dude">
I can see that I have begun to drone on and get a little too technical maybe (for some), but I will give you a hint of how to create web pages which both conform to the W3C standards and display "almost" similarly in both <b>ie</b> and <b>wetscape</b>.
</p>
<h3>How to create cross browser compatability (again, almost)</h3>
<p class="dude">
Always use a "DOCTYPE declaration" in your web documents and most of all use "valid" markup script.
</p>
<p class="dude">
Validate all your HTML and CSS pages using the following link.
</p>
<p class="dude">
<a href="http://validator.w3.org/">http://validator.w3.org/</a>
</p>
<h3>Finals Words</h3>
<p class="dude">
My finals words go to microcrap and <b>wetscape</b>.
</p>
<p class="dude">
Write down all the many and varied ways you have added "to" the W3C recommendations, within your browsers, shout about it to all who will listen and display then on a website of your choosing, but available to all, also stating the following.
</p>
<p class="dude">
<ol class="dude02">
	<li>Any extensions you have added and how they might be incompatable with any other browsers.</li>
	<li>Any tests you have conducted to discover any incompatabilities contained within your extensions.</li>
	<li>Solution as to how to address and resolve these incompatability issues.</li>
</ol>
<h2><b>wetscape</b> Take Note</h2>
<p class="dude">
In <b>ie</b> 5 microcrap invented Conditional comments which enabled ie 5 or higher browsers to hide certain code from other browsers enabling us to add ie specific code to our pages. Why don't you folks stop being so proud and adopt this concept into <b>wetscape</b> and maybe we can all get closer to our dream (yeah sure) of cross browser compatablity some day (when the sun goes super nova, maybe)
</p>
<p class="dude">
Hope it helps ya'll
</p>
<p class="dude">
Let us give fanks to Rudd van Nistelroy and to alex fergeuson and to man utd fer beating arsenal.
</p>
<p class="dude">
P.S. You are welcome to email me (via PSC) if you require either further email or assistance.
</p>
```

