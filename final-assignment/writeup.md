1. [5 points] Write a short profile of each file we have given you. Provide a narrative description of the file (50-100 words per file), including its format, properties, contents, and MD5 checksum. 

Profile for lLO5hsK7EemggQ4qJFCIWA_d27f0da94c8748abb2d364e1438808d7_Consumer_Complaints_FileA.xml:
  - We have an XML file with no internal or external DTD defined. 
  - It's using tabs for indentention with consistent element and attribute naming pattern known as camel casing. 
  - The overall structure looks to be correct and mostly consistent but impossible to know without a defined DTD. Complaint with id 14038 doesn't appear to follow the same element flow like the rest. 

The file appears to be invalid as it contains no DTD definition and with 2 validator error:  

- Document root element "consumerComplaints", must match DOCTYPE root "null"
- Document is invalid: no grammar found.

Elements: consumerComplaints, complaint, event, product, productType, subproduct, issue, issueType,company, companyName, companyState, companyZip, submitted, response, publicResponse and responseType. 

Attributes: id, type, date, via, timely, consumerDisputed

MD5 Checksum: D30CBA6B00308A87FA3A384799C5FAF7


Profile for o-koNMK7EemS6xJ43HxpzA_c97650e0e2494545926e53a8a475c0b8_Consumer_Complaints_FileB.xml:
  - We have an XML file with only one internal DTD entity defined. 
  - It's using tabs for indentention but sometimes with spaces or tabs within the elements. 
  - Consistent element and attribute naming pattern known as camel casing. 
  - The overall structure is inconsistent and hard to follow. Some elements are in new lines and others just continue on the same. There is some consistent order but impossible to know without a defined DTD. 
  - Complaint with id 837784 appears to have a note in comment syntax. 

The file appears to be invalid as it contains no DTD definition and with 122 errors from validator. Most of them being undeclared elements and attributes. 

Elements: consumerComplaints, complaint, event, product, productType, subproduct, issue, issueType,consumerNarrative, company, companyName, companyState, companyZip, submitted, response, publicResponse and responseType. 

Attributes: id, type, date, timely, submissionType, and consumerDisputed

MD5 Checksum: 47677272E76E1F4332AFE859347C8695

2. [7 points] Create a DTD for each XML file. 

Inside `./dtd` folder.


3. [13 points] Canonicalize the two data files and run checksums again to check for equivalence.

lLO5hsK7EemggQ4qJFCIWA_d27f0da94c8748abb2d364e1438808d7_Consumer_Complaints_FileA:
- Ordered attributes in alphabetical order. 
- Removed extra spaces. 
- Used double space for indentation.  
- Created submission element with type attribute to replace submitted and via. 
- Order elements complaint with id 14038 to match others. 

MD5 Checksum: BEF660CD4C17F22AEDEDC7AA6D816AF8


o-koNMK7EemS6xJ43HxpzA_c97650e0e2494545926e53a8a475c0b8_Consumer_Complaints_FileB:
- Ordered attributes in alphabetical order. 
- Removed extra spaces. 
- Used double space for indentation.  
- Remove submissionType attribute and added submission element with type attribute.
- Added missing submission element to complaints with IDs 2364257 and 837784.
- Standardize no to N and yes to Y. 
- Added missing timely attribute on the response element.
- Remove extra space from U.S. BANCORP in line 34.
- Order elements complaint with id 14038 to match others. 

MD5 Checksum: BEF660CD4C17F22AEDEDC7AA6D816AF8

4. [10 points] Create and document the DTD of the final, canonlicalized data file, from step 3 above.

Inside `./final-canonicalized-and-dtd` folder.

lLO5hsK7EemggQ4qJFCIWA_d27f0da94c8748abb2d364e1438808d7_Consumer_Complaints_FileA:
- Ordered attributes in alphabetical order. 
- Removed extra spaces. 
- Used double space for indentation.  
- Created submission element with type attribute to replace submitted and via. 
- Order elements complaint with id 14038 to match others. 

MD5 Checksum: BEF660CD4C17F22AEDEDC7AA6D816AF8

o-koNMK7EemS6xJ43HxpzA_c97650e0e2494545926e53a8a475c0b8_Consumer_Complaints_FileB:
- Ordered attributes in alphabetical order. 
- Removed extra spaces. 
- Used double space for indentation.  
- Remove submissionType attribute and added submission element with type attribute.
- Added missing submission element to complaints with IDs 2364257 and 837784.
- Standardize no to N and yes to Y. 
- Added missing timely attribute on the response element.
- Remove extra space from U.S. BANCORP in line 34.
- Order elements complaint with id 14038 to match others. 

MD5 Checksum: BEF660CD4C17F22AEDEDC7AA6D816AF8

5. [5 points] Be sure that all of your files validate as they will be assessed for compliance to their DTDs. You must test whether your document will validate against your DTD here: http://xmlvalidator.new-studio.org/

File used to validate can be found inside `./final-validated` folder.

6. [10 points] In a separate document, answer the following reflection prompts:

a) Describe your process for canonicalization (i.e., decisions, actions, representation selection, attribute issues, provenance decisions). Report the checksum values after canonicalization.

b) How does the way data is represented impact reproducibility?

c) How may your canonicalization support the overarching goals of data curation (revisit objectives and activities of Week 1)?

d) Which additional curation activities would you recommend to enhance the data set for future discovery and use?

