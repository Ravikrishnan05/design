# design

# Assignment 8 (Refer to session 9)
## List down the expected behavior 
// -bill The software supports easy generation of E-bill 
//and multiple go-downs for processes like batch numbers and
//serial numbers can be done efficiently with this grocery billing software
1.EXPECTED BEHAVIOUR 
*E-bill
 Electronic bill is sent from this app to customer through whatsapp or mail.

*Inventory management
Managing inventory total number of each products that are left and sold,manufacturing date, expiry date,etc..

*Compatible with different payment modes
money can be paid through different payment modes like cash, debit card, credit card, and online payment, etc.
*Easy mobile operation
it should provides an interactive touchscreen for cashiers to provide easy and faster checkout.
*Promotions management
it will send customers discounts and vouchers based on the shopping they have done .
*GST reports
it will apply variable GST on different products on the basis of their category and type
## and show the structure of your product/service in graphical form
2.Structure of product 
Presentation Layer-------UI -blue dominant colors,calbiri fonts,tabular placement.
     |             -------UX -easy operation for user.
     |
     |
Business layer  -------business logic-algorithms of python or c code, calculations,code.
     |           -------Data Processing- interacting with the data layer or presenting it to the user.
     |          -------Workflow Management-It manages the flow of operations within the application.
     |
Data layer    -------Data Storage-using (MYsql) responsible for creating, updating, deleting data 
              -------Data Synchronization-data stay up-to-date.
              -------Transaction Management-supports transactions in the shop
## What are the key functions required of your product/service?
                              
Sending E-bill
easy mobile operation
Inventory management 
payment through it 
sending offers 

Explaination for relations 
|Sending E-bill impact sending offers because we can use bill as a medium
for our advertisement of offers and discounts.
|easy mobile operation(better UI/UX) impacts almost every process that we do using that moblie app.
it makes every process easy.
|Inventory management doesnt impacts any other significanty.
|payment through app make sending E-bill,inventory management easier and automated.
we can give offers like cash back while paying through app.
|sending offers impacts payment through app because if we give offer like(10% cash back if you 
pay through app then a lot will start to pay through the app.

Critical intervention points
Inventory management -Analyzing inventory levels and turnover rates can reveal areas for optimization,
                      reducing stockouts, minimizing excess inventory costs, and
                      improving overall supply chain management.
Construct ISM for your product/service and identify the hierarchy levels for your product functions


Sending E-bill
easy mobile operation
Inventory management 
payment through it 
sending offers 
