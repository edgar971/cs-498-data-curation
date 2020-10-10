# Assignment 2: XML Schema Design Exercise by Edgar Pino (edgarsp2)


### [10 points] Write prose documentation for each element, attribute, and attribute value.

My process for creating the DTD was just going through the document and identifying key parts while having the activities and objective of the data curation process in mind. 
This was a blog post so elements like Article, Title, and Author made sense. I was thinking how this document was going to be shared, organized, accessed, discovered, and stored. 
Seeing how XML can be parsed and viewed in many ways led me to the structure I defined and the names of my elements and attributes. 

Elements:
- Article: The whole article page.
- Title: The title of the article. Can be used to show it quickly on a user interface. 
- Date: The date of which the article was published. Can be used by a search index to rank articles by dates. 
- AuthorName: The one or many author names in their article.
- ArticleLength: The article length in minutes that it takes to read.
- Body: The actual body of the article.
- Section: Individual sections of the article for key ideas.
- Heading: The heading title of the section.
- Image: An image that's part of a section.
- Link: A link to an external page.
- Paragraph: The actual text paragraph in the section.
- OrderedList: An ordered list of items.
- HighlightedText: A piece of text that is highlighted to draw attention.

Attributes: 
- Image src: The source URL of the image to show. 
- Image description: The image description to show below or on hover. This is useful to either display to the user or to provide more searchable information. 
- Date timezone: The timezone of the articles published date. 
- ArticleLength minutes: The number of minutes of the article. 
- Link to: The URL where the link should take you including other documents for quick access.
- Link external: To know if the link is external to the current document. This can be used to display the link differently in a web search or to crawl and index all external websites. 

### [25 points] Write a narrative about this process, answering the following reflection questions:

#### How did you decide to represent the data in the way that you did? Why did you choose the elements and attributes that you did? 
My process was the look at the document I was converting for key identifier elements while keeping the objective of data curation in mind.
Right away I saw a few that made sense for example: AuthorName, Title, Image, and Link. This can be used to show authors in a quick search as well the article title.
Some I had to think harder as I had to figure out the best descriptive names. I did the same for the attributes since the link and image were straightforward.
 
One thing that helped me was my knowledge of HTML.


#### What were the hardest decisions you had to make in this design process?
I feel like naming is always the hardest part, creating descriptive and straightforward names can be challenging. 
One other problem I had was deciding on what activities to focus on.
There are many I could have chosen to focus on but I selected Sharing, Discoverability, Accessibility, Storage, and Organization 
because XML focuses on encoding readable documents for humans and machines.


#### How does your DTD design support data independence?
Overall by being generic enough to be reused and also straightforward to understand. My DTD doesn't not care how it's stored, formatted, and displayed.
It's able to be parsed by humans and machines.


#### How may your DTD design support the overarching goals of data curation (revisit objectives and activities of Week 1)?
I feel like my DTD design supports the goals of data curation by enabling reuse over time, human and machine readable, and storage agnostic.
The text here can be parsed, validated, and also viewed easily.
I also think it supports activities like Sharing, Discoverability, Accessibility, Storage, Organization and others for the following reasons:
 
1. Having a clear and descriptive document structure.
2. Supporting many forms of storage.
3. Being able to access the information in many ways like a website with search.
4. Easy to share given that XML is flexible and supported in many systems.
 
It supports the data curation objective of efficiently and reliably allowing analysis and reusability of data over time because the DTD design is flexible 
and can be stored, read, and displayed in many ways. 


#### What are the pros and cons of your DTD design?
The pros for me would be the clear names of the elements and attributes as well as the document structure.
One pro I can think of is the order of the elements, it was one of the problems I ran into. I wish there was
way to define the elements without strict order.



