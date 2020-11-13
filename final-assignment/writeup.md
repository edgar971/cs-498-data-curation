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
  - Complaint with id 837784 appears to have a note inside like a comment. 

The file appears to be invalid as it contains no DTD definition and with 122 errors from validator. Most of them being undeclared elements and attributes. 

Elements: consumerComplaints, complaint, event, product, productType, subproduct, issue, issueType,consumerNarrative, company, companyName, companyState, companyZip, submitted, response, publicResponse and responseType. 

Attributes: id, type, date, timely, submissionType, and consumerDisputed

MD5 Checksum: 47677272E76E1F4332AFE859347C8695

