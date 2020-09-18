## How did you decide to represent the data in the way that you did? 


My database design was based on the 3 files from the auto dealer. I decided to create 5 different 
tables based on the data needs from the three different departments: customers, inventory, sales, and vehicles. 

- customers: This table has all existing customers including those with a sale and potential.   
- inventory: This table contains all available vehicles for sale. 
- sales: Holds sale information including vehicle, customer, and related sale metadata. 
- vehicles: Contains specific vehicle information like year, make, and model. 


## Did you leave out any information? If so, why?
I didn't leave any information out. I believe all data was useful and it can always be hidden from any GUI or completely removed from the database. 

## Why did you choose certain things as attributes? As keys? 
Most if not all attributes came from the three different files we got. I added a few extra which I thought to be of benefit like dates and primary keys. All tables have incremental primary key ids. This is in order to have foreign keys with other tables. 

## What were the hardest decisions you had to make in this design process?
One of the hardest decisions I made was how much to normalize the database. For example, I could have split the customer table to support multiple addresses. 
I also had to think about the table and column names in a way that made sense. 

## How does your schema design support data independence?
My schema design supports data independence because I can change any of the data with foreign keys without 
affecting where it's being used. For example, I can update the customer address and I don't have to update 
the sales or leads table due to the foreign key. Also, any interface using this data doesn't have to get updated. 


## How may your schema design support the overarching goals of data curation (revisit objectives and activities of Week 1)?
My schema design supports the overarching goals of data curation by allowing data to be reused.

## What are the pros and cons of your schema design?
The pros of my data design is clean data, reusability, modifiable, and overall easy to work with. One of the cons I can think of is maybe more work to create records if any of the foreign rows don't exist. Another pro is not being able to delete a row if there's a dependency on it. 

## Which curation activities could enhance or sustain the database for future discovery and use for new purposes? What additional activities would you recommend?
One way to promote future discovery and use for new purposes is to promote data sharing between teams and departments, integration, and communication to provide useful insights. 


