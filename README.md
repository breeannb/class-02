# class-02

# Read 02

_________

# HTML & CSS
# 1. Chapter 2: "Text" pp. (40-61)
- **Structural Markup** - the elements that you can use to describe both headings and paragraphs
- **Semantic Markup** - provides extra information, such as where emphasis is placed in a sentence, that something you have written is a quotation (and who said it), the meaning of acronyms and so on. 
- HTML elements are used to describe the strucrture of the page (eg. headings, subheadings, paragraphs)
- They also provide semantic information (e.g where emphasis should be placed, the defiition of any acronyms used, when given text is a quotation.)

Headings
* there are six levels of headings ranging from < h1> to < h6>
* these are displayed in different sizes but can also be controlled in CSS

Paragraphs
* < p> - a browser will show each paragraph on a new line with some psace between it and subsequent paragraphs

Bold and Italic
* < b> - bold and is also related to the < strong> element

< i> - Italic and can be used for technical terms, names of ships, foreign words, thoughts

Subscripts & superscript
* < sup> - used to contain characters that should be superscript, such as suffixes of dates and mathematical concepts like raising a number to a power 2<sup>2</sup>
* < sub> - contain characters that should be subscript. Commonly used for foot notes or chemical formulas such as H<sub>2</sub>O

Whitespace
* whitespace collapsing - when a browser comes across two or more spaces next to each other, it only displays one space.

Line Breaks and Horizontal Rules
* < br /> -add a line-break in the middle of a paragraph
* < hr /> - break between themes, such as a change of topic in a book or new scene in a play.  
**Empty Elements** - elements that do not have any words between an opening and closing tag and usually will only have one tag

Semantic Markup - text elements that are not intended to affect the structure of your web pages, but they do add extra information to the pages.
* Strong and Emphasis 
    * < strong> - shows elements in bold
    * < em> - italic
* Quotations 
    * < blockquote> - used for longer quotes that take up an entire paragraph and the < p> element is still within the blockquotes. 
    * < q> - used for shorter quotes that sit within a paragraph, and some browsers will put a quote around it. 
* Abbreviations and Acronyms
    * < abbr> - will give a title attribute and display the full text of the abbreviated texxt if hovered over
* Citations and Definitions
    * < cite> - to reference peice of work or book
    * < dfn> - first time new terminology is explained 
Author Details 
    * < address> - contain contact details for author of the page
Changes to Content 
    * < ins > & < del> -inserted and deleted content
    * < s> - no longer accurate or relevant

# 2. Chapter 10: "Introducing CSS" pp.(226-245)
Understanding CSS: Thinking Inside the Box
* imagine that there is an invisible box around every HTML element. Css allows you to control each box
* CSS ASsociates Style Rules with HTML Elements 
    * CSS Rule has two parts: 
        1. selector - indicate which element th rule applies to
        2. declaration - indicate how the elements referred to in the selector should be styles. This can be split into two things, a property and value. 
            * Properties - indicate the aspects of the element you wnat to change such as color, font
            * Values - specify the settings you wnat to use for the chosen properties, such as color of yellow
* External CSS
    * < link>
    * href - path to css file
    * type - type of document linked to
    * rel - relationship between HTML page and file linked to
* Internal CSS 
    * < style> -can also include CSS rules within HTML page and usually sits in the head element
* CSS rules usually appear in a seperate document, though they may appear in the HTML page

________

# VOCABULARY

# Chapter 2: "Basic Javascript Instructions" pp.(53-84)

- **Statement** - Each individual instructin or step within a script
- **code block** - statements within { }
- **comments** - explain what your code does /* or Cmd+/
- **multi-line comments** - starts wiht /* and ends with */ for lines of comment that stretch over one line
- **single line comments** - anything that follows two forward slash characters // contained in one line
- **variable** - script's storage of bits of information to do its job
- **delcare** - to create a variable and give it a name
- **assign a value** - once you create a variable, you can tell it what info you would like ti to store
- **array** - special type of varialbe. It stores a list of values.
- **array values** - are accessed as if they are in numbered list. 
- **expression** - evaluates into (results in) a single value. there are two types of expressions
- **operators** - allow programers to create a single value from one or more values
- **string Operator** - the + symbol and is used to join the strings together inside of it

# Chapter 4: "Decsision and Loops" pp.(145-162)
- **comparison operators** - compare values an dtest wheather a conditions is met or not
- **decisions** - an expression is evalues, which returns a vlue and a conditional statement says what to do in a given situation 
- **switch statement** - starts wiht a variable called a switch values. Each case indicates a possible value for this variable and the code that should run if the variable matches the value. 