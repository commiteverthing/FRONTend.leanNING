What are tags ?

Tags are the markup entity, In simple words tags are the special words that helps us to give structure ,meaning , formatting(underline , bold, strick ).


What are Semantic Elements?

Semantic tags clearly describes its meaning to both the browser and developers.
eg: <img>, <table> , <article> .



What are Non-Semantic Elements?

Non-Semantic Elements tags tells nothing about its content .

eg <div> ,  <spam>



What is HTML <section> Element ?

Section element defines a section in the documents.

Eg of section element are under;

- News.
- Chapter. 
- Introduction's.
-  Contact informations.

<section>
<h1>WWF</h1>
<p>The World Wide Fund for Nature (WWF) is an international organization working on issues regarding the conservation, research and restoration of the environment, formerly named the World Wildlife Fund. WWF was founded in 1961.</p>
</section>

<section>
<h1>WWF's Panda symbol</h1>
<p>The Panda has become the symbol of WWF. The well-known panda logo of WWF originated from a panda named Chi Chi that was transferred from the Beijing Zoo to the London Zoo in the same year of the establishment of WWF.</p>
</section>



👉 The <article> tag is used for content that is independent or self-contained, meaning:

it can stand on its own
it still makes sense outside the page
it can be reused or shared separately


What is HTML <header> Element ?

The header element reperesent's a set of navigational link .

A header element typically contains 

. one or more heading elements (h1 - h6)
. logo or icon 
. authorship information


NOte : we can have serval header element in one HTML document, However, header cannot be placedwithin a footer , address , or another <header > elemnt .

eg:
<article>
  <header>
    <h1>What Does WWF Do?</h1>
    <p>WWF's mission:</p>
  </header>
  <p>WWF's mission is to stop the degradation of our planet's natural environment,
  and build a future in which humans live in harmony with nature.</p>
</article>


What is HTML <footer> Element ?

The <footer> element defines a footer for a document or section.

A <footer> element typically contains:

authorship information
copyright information
contact information
sitemap
back to top links
related documents
You can have several <footer> elements in one document.

eg :<footer>
  <p>Author: Hege Refsnes</p>
  <p><a href="mailto:hege@example.com">hege@example.com</a></p>
</footer>



What is HTML <nav> Element ?

The <nav> element defines a set of navigation links.


eg:<nav>
  <a href="/html/">HTML</a> |
  <a href="/css/">CSS</a> |
  <a href="/js/">JavaScript</a> |
  <a href="/jquery/">jQuery</a>
</nav>
