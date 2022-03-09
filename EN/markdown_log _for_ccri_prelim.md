## Tackling the ugly problem

## In the beginning
1. On the negative side
- a great deal of information and many sections are crammed into one long page. It looks junky. <br/>
2. On the plus side
- Sandra had created a table of contents at the top of the page to make this massive page more navigable (via html links to t ## - level headers) 
- \## - level headers display horizontal lines on the line just below and are good section demarcators.  
<!-- the backslash before ## in the line above let's you to sneak in text that Markdown knows as a format tag -->
3. Prep:
- Shannon installed Atom and the markdown preview package
- Markdown testing.  We commented our test changes for tracking, e.g., \<!-- Susan TO SHANNON, changed to xyz, do you like this? -->    
We will delete most of these comments as soon as we have a good handle on what we are doing.
4. We looked at ways of: 
- Improving spacing (like more white space);
- Improving flow (clearer hierarchy and progression, keeping explanations short and presentation more consistent). 
5. We want clearer and consistent line breaks between sections, proportionate to the hierarchy of the sections. 

## Solutions so far
### 1. Spacing
1.1 A good idea is to standardizing the line breaks between sections - probably to a maximum of four line breaks before new ## headers. 
1.2 We are looking at how to control line breaks more.
#### Method
- The page now controls line breaks with two spaces at the end of the line above.  
- This reflects best practises A, B and C.  

A) ONE line break    
First line with two spaces after.     
And the next line. 
<!-- One line break -->
 
B) TWO line breaks  
Line with two spaces after.     

More brilliant blah blah.  
<!-- Two line breaks -  the two spaces in the first line may be optional in this case, but not sure -->. 
C) TRHEE line breaks  
Line with two spaces after   


More blah blah. 
<!-- Three line breaks - needs the two spaces in the first line -->

D) FOUR LINE BREAKS.   
Line with two spaces after     
<br/>\<br/>


More blah blah
<!-- Four line breaks - needs the two spaces in the first line  -->

### More consistent formatting 
1. Susan added sub-header numbers to unnumbered sub-headers.  We probably won't number the sections above CCRI Data Sources: 1 Selected published data tables be numbered.  This would create numbering like 2.2.3.1.1.
2. Any sections that look weird probably need to be formatted like the others

### It's too much!
1. Just so much crammed is into **2. Microdata**.  
2. Susan will work on a detailed table of contents for this cluttered CCRI Data Sources section.

#### Method

Part 1. 

I used a Markdown table for table of contents because it gives more readability with alternating shaded rows for this great big blob of content links.
Just a small related point, I also got rid of text centering for everything under the header row by taking off the colons, so that
| :----: | :----: | :----: |
became:
| ---- | ---- | ---- |

Part 2.

Used workaround for this table:
1. I used the superscript format <sup>blah blah<sup/> all to create a small font.  Otherwise the table of contents is massive and onerous to read.    
I don't think the offset superscript text positioning is a biggie.  
2. I got rid of all the periods in the section numbering, so 1.2 became 1-2.   
This one change lets us create internal page links to the CCRI data sources section headers.    
E.g., using the interim URL of this page, " https://github.com/SusanMowers/reCens_doc/blob/main/EN/ccri-prelim.md", the link to the ### 1-2  header becomes: 
4. In the first column, I stuffed in a leading space before the section number that had more than one character, so *1-2* became *&nbsp; 1-2*
