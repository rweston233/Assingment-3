# Assingment-3

## Assignment 3 Learning Objectives

### Part I
> Creating an EER Diagram using MySQL Workbench

- For part I, create an EER Diagram using MySQL Workbench for a store with employees.

- Using the rules below build an EER diagram.  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;  - The store has employees (ID, last, first, hire date, release date, manager)  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;  - All employees must work at a store  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;  - An employee may have a manager  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;  - An employee can be assigned to more than one store  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;  - A store can have more than one employee  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;  - All stores belong to a region  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;  - A store can be in only one region  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;  - Add relationship labels to All relationships  

**Part I Deliverables**
- Create a schema named `assign03`.
- Forward engineer the model and save the SQL that creates the model as `cit381-assign03-store.sql`.
- Save the model as `cit381-assign03-store.mwb`.
- Use Workbench to export an image (PNG) of the model as `cit381-assign03-store.png`.


### Part II
> Create another EER Diagram using MySQL Workbench.

- Create an EER Diagram using MySQL Workbench for an auction web site. Below are the requirements for this EER Diagram.

- **Using the following paragraph extract the rules to create a schema and EER diagram:**  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; - An auction web site has items for sale that are provided by sellers. Each item has an opening price, a reserve price, a description, and an ending time. Customers submit bids. The highest, earliest bid submitted before the ending time is the winning bid and the item is sold to the bidder. The auction company wants to be able to analyze the sales behavior of its customers and sellers and so must keep track of all bids and sales.  

**Part II Deliverables**
- Create a schema named `assign03`.
- Forward engineer the model and save the SQL that creates the model as `cit381-assign03-auction.sql`.  
- Save the model as `cit381-assign03-auction.mwb`.
- Use Workbench to export an image (PNG) of the model as `cit381-assign03-auction.png`.

#### Deliverables
[assign03.zip](https://github.com/rweston233/Assingment-3/blob/main/assign03.zip)

>> Back to home page:
[Home](https://rweston233.github.io/)
