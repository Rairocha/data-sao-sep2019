![Ironhack logo](https://i.imgur.com/1QgrNNw.png)

# Lab | MySQL

## Introduction

As a data expert you work at a car dealership company which sells new cars of various brands and models. Your company is small and new but it has branches in several countries. Since the establishment of the company your colleagues have sold several cars to the customers. Now your boss realized your company imperatively needs a database to keep the records about the cars, salespersons, customers, and invoices. Your boss trusts you very much so he assigned you the challenge to design, create, and manage the database.

## Challenge 1 - Design the Database

Using pen and paper (or computer software if you are skillful at creating digital diagrams), design a database to meet the minimal requirements of your boss. The minimal information to be recorded is described below:

1. **Cars** - e.g. the vehicle identification number (VIN), manufacturer, model, year, and color of the cars in your company's inventory.

1. **Customers** - e.g. the customer ID, name, phone number, email, address, city, state/province, country, and zip/postal code of the customers.

1. **Salespersons** - e.g. staff ID, name, and the store at your company.

1. **Invoices** - e.g. the invoice number, date, car, customer, and salesperson related to each car sale.

Before solving this challenge, review your lesson about database structure and design then ask yourself:

* **What entities and attributes should be included in the database?**
	* For each attribute, what data type is most suitable?
	* Note that in MySQL typically each entity table should have an auto-increment numeric ID. The auto-increment ID is different from the customer ID or staff ID.
	* Also note that some attributes are required while other ones can be blank.

* **What are the relations between these entities? Which relations are one-to-one vs one-to-many vs many-to-many?**

* **How can you use foreign keys to normalize your database design?**

Your end product of this challenge should look something like below, though it doesn't have to be that complicated:

![ERD](https://s3-eu-west-1.amazonaws.com/ih-materials/uploads/data-static/images/erd.png)

If you use pen and paper to create the design, take a picture with your phone and send the image to yourself. If you use software to create the database diagram, export in the image format (JPG or PNG). Either way, the image will be submitted as one of the deliverables.

