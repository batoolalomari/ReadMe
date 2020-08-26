
# Superscript & Subscript
## <sup>
The **<sup>** element is used to contain characters that should be superscript such as the suffixes of dates or mathematical concepts like raising a number to a power such as 22.

## <sub>
The **<sub>** element is used to contain characters that should be subscript. It is commonly used with foot notes or chemical formulas such as H20.
  
   Element | Example
  -------- |--------
  <sup> | <p>On the 4<sup>th</sup>
  <sub> | <p>The amount of CO<sub>2</sub>
    
   # White Spaces
    
 In order to make code easier to read, web page authors often *add extra space*s or start some elements on *new lines*.
 **white space collapsing** : When the browser comes across two or more spaces next to each other, it only displays one space. Similarly if it comes across a line break, it treats that as a single space too.
 **Ex**:
- <p>The moon is drifting away from Earth.</p>
- <p>The moon is drifting away from Earth.</p>
- <p>The moon is drifting away from
- Earth.</p>

**But** if you wanted to add a line break inside the middle of a paragraph you can use the line break tag **<br />**.
 
 # Empty elements
 TIs the elements that do not have any words between an opening and closing tag and usually has only one tag. Before the closing angled bracket of an empty element there will often be a space and a forward slash character.
 
# Horizontal Rules
To create a break between themes — such as a change of topic in a book or a new scene in a play — you can add a horizontal rule between sections using the **<hr />** tag.
**EX**:
<p>Venus is the only planet that rotates clockwise.</p> <hr />

# Semantic Markup
The text elements that are not intended to affect the structure of your web pages, but they do add extra information to the pages.
For example,the **<em>** element that allows you to indicate where emphasis should be placed on selected words and the <blockquote> element which indicates that a block of text is a quotation.
  
  **EX :**
  <p>I <em>think</em> Ivy was the first.</p>
  
  *Strong Emphasis***
  The use of the <strong> element indicates that its content has strong importance.
  **EX**:
  <p><strong>Beware:</strong> Pickpockets operate in
  this area.</p>
  
  
# Quotations :
*There are two elements commonly used for marking up quotations:*
# <blockquote>
The <blockquote> element is used for longer quotes that take up an entire paragraph. Note how the <p> element is still used inside the <blockquote> element.

#<q>
The <q> element is used for shorter quotes that sit within a paragraph. Browsers are supposed to put quotes around the <q> element, however

**Both elements may use the cite attribute to indicate where the quote is from. Its value should be a URL that will have more information about the source of the quotation.**
  
  **EX:**
  <blockquote cite="http://en.wikipedia.org/wiki/
  Winnie-the-Pooh">
  <p>Did you ever stop to think, and forget to start
  again?</p>
  </blockquote>
  <p>As A.A. Milne said, <q>Some people talk to
  animals. Not many listen though. That's the
  problem.</q></p>
  
 # Abbreviations & Acronyms :
 **<p><abbr title="Professor">Prof</abbr> Stephen Hawking is a theoretical physicist and cosmologist.</p>**
 
# Citations & Definitions
**<cite>**
 the <cite> element can be used to indicate where the citation is from like When you are referencing a piece of work such as a book, film or research paper
**Ex**:
  <p><cite>A Brief History of Time</cite> by Stephen
  Hawking has sold over ten million copies
  worldwide.</p>
  
 **<dfn>**
The first time you explain some new terminology (perhaps an academic concept or some jargon) in a document, it is known as the defining instance of it.
The <dfn> element is used to indicate the defining instance of a new term.
  **Ex** 
  <p> A <dfn>black hole</dfn> is a region of space from which nothing, not even light, can escape.</p>
  
  
  # List
  There are three type of Lists:
  
  List  | Def   | Ex
  ----- | ----- | -----
  orderd | lists where each item in the list is numbered. |<ol><li>Chop potatoes into quarters</li></ol>
  unorderd | lists that begin with a bullet point | <ul><li>Chop potatoes into quarters</li></ul>
  definition | are made up of a set of terms along with the definitions for each of those terms. | <dl><dt>Sashimi</dt><dd>Sliced raw fish</dd></dl>
  
  
  
  
  
 
 
    
