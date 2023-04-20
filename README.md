# referance-website
1. Naming convention for all filenames, paths and folders
- All lowercase
- no spaces
- only letters, numbers, and dashes

2. Best practices for commit messages
-  one that explains what was changed, and why a change was made

3. What is HTML?
- hypertext Markup Langueage  

4. Proper syntax for HTML tags
- The tags used to define the purpose of the text follow a specific synatax.

5. Explain or demonstrate commonly used html tags/elements:
headings: h1-h6 
- The heading tags are used to mark heading according to their importance. (h1) stands for the most important heading. (h6) stands for the least important and the smallest one.

p
- Defines a paragraph of text. it is a block-level element and always starts on a new line. 

lists: ul, ol, dl
- (ul) unordered list
- (ol) ordered list
- (dl) description list

a
- The opening <a> tells where the link should start and the closing </a> indicates where the link ends. To create a hyperlink, you should use the <a> tag and href attribute, the value of which is the URL, or location, where the link is pointing to

img
- Images in websites are not embedded in the website, but linked to by the HTML document. Images need two attributes to specify extra details about the image: the location of the image and the alternative content 

q
- used to mark up quotes embedded in other elements like a paragraph. 

blockquote
- For large stand alone quotes.

cite
- Marking the source of the quote. 

em
- Emphasis 

strong
- lots of emphasis, strong importantance or urgency.

b
- A keyword 

i
- another language, technical term, title

small
- is used to represent side-comments and small print. such as copyright and legal text.

6. Explain block Elements and also explain the list of block elements and why they are used from below:
- a block element is an HTML element that begins a new line on a web page and extends the full width. 

html
- is the language for describing the structure of web pages. 

head
-  contains machine readable information (metadata) about the document and its title, script, and style sheets.

body
- is used to reperesent the content of an HTML document. There can only be one <body> element in a document. 

header
- is the introductory content usually at the top of the page and would include a logo or company name and main navagation. headers can also bewithin the sections and articles to introduce the conent for headings, subheadings, author, and so on.

nav
- nav is an element that represents a section of a page whose purpose is to provide navigation links, either within the current document or to another document. 

main
- The main element wraps around the main content of the page. the main is only used once per page and it tells the browser that this is where the main content is located. 

section
- the section is used to wrap around related pieces of content. usually each section has its own heading. 

article
- The article element represents a self-contained composition in a web page, which is intented to be independently distributable or reusable. 

div
- block element used to group elements together. 

aside
- aside is an element that represents a portion of a document whose conent is only indirectly related to the documents main content. this will frequently be presented as a sidebar on a website.

footer
- The footer is at the bottom, which often includes lists of links, copyright information, extra information about the company, terms and services.

span
- an inline container used to mark up a part of a text, or part of a document.

small
- is used to represent side-comments and small print. such as copyright and legal text.

7. Explain why accessibility is important and also explain the accessibility properties like:
- Accessibility is important as it allows users with disabilities, will have an ideal experience and can access the information equally. web accessibility means everyone. 

landmark roles
- to help those using screen readers to cump directly to the specific sections within our sites. 

aria labels
- adding the aria labels provides the user with non visual label that will only be announced by screen readers.

image alternative texts
- the two main purposes for the alt attribute is to describe the photo if it doesnt dowload. and to describe the photo to someone who is unable to see the image, possibly someone who is using a screen reader. 

8. What is CSS and how can we implement CSS to our html file (write a proper explanation with the code required to attach a CSS file inside html file)
- CSS stands for Cascading Style Sheets, It is used to control the appearance of the HTML pages. When adding a CSS file to an HTML file you need to link the CSS file to the HTML so that the bowser will know where to find the CSS file. The code to attach a CSS file inside a HTMl file is (The <head> of the html document using the <link> element.)

9. What is the difference between CSS property and value (write explanation and an example code)
- a property is an aspect of a selector. a value is a possible setting for a property.

10. Why do we use border-box property in CSS?
- border-box tells the browser to account for any border and padding in the values you specify for an elements width and height. 

11. Explain different type of ways we can add spacing to an element.
- adding padding
- adding a border
- adding margins

12. What is the main difference between margin and padding?
- the main difference between margin and padding is that passing is the space between the elements content and its border. while margin is the space between the elements border and the next element. 

13. What are different types of display properties?
- 

14. Write a brief explanation of flexbox property?
- flex box property is designed as a one dimmensional layout model. also as a method that can offer space distribution between iteams in an interface and powerful aligment capabilities. 

15. What are different types of flexbox properties and what is the major difference between them?
- flex-direction
- flex-wrap
- flex-flow
- justify-content
- align-iteams
- align-content

16. Explain with code the use of flexbox property on a parent element and also explain the sub properties you might need for the flexbox property.
- flex container and for sub properties its flex direction, justification and aligment, and wrap.

17. Write a code example on how you will use a flexbox property on a parent element with sub properties.
  <section>
    <div></div>
    <div></div>
  <section>
- section {
    display: flex;
    flex-direction: column;
    flex-wrap: nowrap;
    justify-iteams: space-between;
    align-iteams: baseline;
}
18. What is CSS grid property?
- CSS grid property is a shorthand property that sets all of the explicit and implcit grid properties in a single declaration. 

19. Write the parent and two sub-properties used for CSS Grid Property.
- parent= is grid container and the sub properties =display grid and grid templates. 

20. What is the difference between display: flex and display: grid?
- Flex box was created for the layout in one dimension, either a row or a column. Grid is designed for two dimensional layouts, rows, and columns at the same time.

21. What sub-property we use to divide elements in CSS Grid properties?
- grid-templates-rows

22. What unit we use to fractionally divide the element width in CSS Grid property and what are others unit we can use alternatively? (Write a code example)
- the unit is fr but you can also use % and px too.

23. What is the area property in CSS grid we use for the child elements?
- grid-area

24. Which sub-property of display grid you can use to prevent displaying empty columns. Write a code example of that property.
-grid-gap 

25. Explain the steps to add google fonts to your CSS file and how will you link it to the html file.
- to add google fonts to your CSS file you first go to google fonts, search your font that you need. Then you slect the font on the right hand side. once you have selected the font click on "few font family" there you will see what fonts you have selected and at the bottome it will say use on the web and you coppy the link and place it in the HTML, then you copy the CSS rules to specify families and place that into your CSS file.,  
