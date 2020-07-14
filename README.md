# homework-2
In an effort to streamline the structure of the HTML and CSS, and in order for an easy read for those who are not familiar with web developing or understanding CSS/HTML or Syntax, there was a lot of vanilla wording in the CSS coding by using terms such as ".benefit-item" to identify tag names and ".infobox" in order to identify a class name. Each pieces of conent was met with same width, display and margins which were redundant. So "aside" was used as a tag name that would be utilized for benefit item, infobox img, and infobox h2 in order to be more streamlined. 
There were too many header lines with the same color, font, and padding (pixils), so all of those classes and tag names were removed that were redundant and one container was used to identify the classes. 

The example below is pre-HTML5 and the current Semantic tags in order to get an understanding how the webpage layout works. 

<img
src="https://www.webcodegeeks.com/wp-content/uploads/2015/06/html5-structure.jpg">

PRE-HTML5 Way of doing things (Old Way)
=========================
<div class="navigation"></div>
<div class="top-header"></div>
<div class="content">
  <p>Some paragraph about something blah blah</p>
  <p>Another paragraph about something blah blah</p>
</div>
<div class="side-bar"></div>
<div class="footer"></div>

HTML5 Way of things (New Way)
===================
<nav></nav>
<header></header>
<section>
  <article></article>
</section>
<aside></aside>
<footer></footer>
*** these are the new SEMANTIC tags

In collaboration with webcode geeks and Fred Rodolfo

HTML: 
file:///Users/mariomacias/ucb-sfc-fsf-pt-06-2020-u-c/01-HTML-Git-CSS/02-Homework/Develop/index.html
