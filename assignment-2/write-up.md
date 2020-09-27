# Assignment 2: XML Schema Design Exercise by Edgar Pino (edgarsp2)


### [10 points] Write prose documentation for each element, attribute, and attribute value.

My process for creating the DTD was just going through the document and identifying key parts of it. This was a blog post so elements like Article, Title, and Author made sense. 

Elements: 
- Article: The whole article page. 
- Title: The title of the article. 
- Date: The date of which the article was published. 
- AuthorName: The one or many author names in thei article. 
- ArticleLength: The article lenth in minutes that it takes to read. 
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
- Image description: The image description to show below or on hover. 
- Date timezone: The timezone of the articles published date. 
- ArticleLength minutes: The number of minutes of the article. 
- Link to: The URL where the link should take you to. 

### [25 points] Write a narrative about this process, answering the following reflection questions:

#### How did you decide to represent the data in the way that you did? Why did you choose the elements and attributes that you did? 
My process was the look at the document I was converting for key identifier elements. Right away I saw a few that made sense
for example: AuthorName, Title, Image, and Link. Some I had to think harder as I had to figure out the best descriptive names. 
I did the same for the attributes since link and image were stright forward. One thing that helped me was my knowledge of HTML. 

#### What were the hardest decisions you had to make in this design process?
I feel like naming is always the hardest part. Coming up with names that make sense and are descriptive enough. 


#### How does your DTD design support data independence?
It's generic enough to be reused and also strightforward to understand. 


#### How may your DTD design support the overarching goals of data curation (revisit objectives and activities of Week 1)?
I feel like my DTD design supports the goals of data curation by enabling reuse over time. The text here can be parsed, validated, and also viewed easily. 
I also think it suppports the following activies: Sharing, Discoverability, Storage, and Organization. 

#### What are the pros and cons of your DTD design?
The pros for me would be the clear names of the elements and attributes as well as the document structure. 
One pro I can think of is the order of the elements, it was one of the problems I ran into. I wish there was 
way to define the elements without strict order. 


