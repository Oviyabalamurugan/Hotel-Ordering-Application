# Hotel-Ordering-Application
 
## Abstract:
The food sector is extremely labour-intensive, and the cost of hiring the right people to accomplish the job is the most significant expense. One option to cut costs is to employ contemporary technology to automate some of the jobs that would otherwise be done by humans. We suggest an "Online Food Ordering System" in this project. An online food ordering system can be defined as software that allows restaurant businesses to accept and manage orders placed over the internet. The technique can be utilised in any industry that delivers meals. Because the entire process of processing orders is automated, this simplifies the food ordering procedure for both the client and the restaurant. The goal of this project is to create a Web-based ordering food application that includes New Order, Order History, Restaurant Profile, Order Status, Order Tracking, and Reviews/Feedbacks. This technique will enable hotels and restaurants to expand their company by lowering personnel costs. Customers pay with their credit cards, albeit they can be served even before making a cash or credit card payment. Our online ordering systems generally consist of 2 main components. First is a website for hungry customers to view the restaurant's dishes and place an online order. Second is an admin management interface for the restaurants to receive and manage the customer's orders.

## :heavy_check_mark: Modules:
1) Login/Sign UP
2) Online ordering  
3) Searching a restaurant
4) Payment
5) Order Tracking
6) Review/Rate a Restaurant/Food

## Forms used: 
* Signup Form
* Login Form
* Address From 
* Payment From
* Feedback Form


## Reports to be generated:                     
1) Transactions Report: Reviewing this report will allow to track production, see staff errors, calculate the loss of revenue
2) Food Report: Reviewing this report will allow us to track the most ordered ,least ordered and the categories .
3) Customer Report: Reviewing this report will allow us to track the customer details and their respective orders.
4) Average Daily Rate: Reviewing this report will allow you to benchmark your property.
5) User Feedback Report : Reviewing this report will allow us to improve the quality as well the service.

## Software tools for Building the App : 
* Visual Studio Code
* MariaDB Server (for MySQL)
* Reactjs

## Hardware tools for Building the App :
* Processor: Intel core i7 10th gen or Newe
* RAM: 16GB or Higher
* Storage: 1TB SSD or Higher
* Screen: 15.6 inch or Higher, 1920 x 1080 pixels


## Tables:

Master Tables:

Customer Table : To Track the Customers who ordered the particular food.

Customer_id (PK)

Employee Table : To track details of the employee.

Employee_id (PK)

Menu Table : To track the quantity of the food.

Menu_id (PK)

Supplier Table : To track the number of suppliers and to keep track of the ordered food in  a particular hotel.

Supplier_id (PK)

 

 ---------------------------------------------

 

Transaction Tables:

Payment Table : To have detailed information regarding the Payment made by the customer.

Payment_id (PK)

            Customer_id (FK)

            Order_id (FK)

            Food_id (FK)

            Supplier_id (FK)

            Payment_id (FK)  

---------------------------------------------------



OrderFood Table :  To track the details of the food to be delivered

Order_id (PK)

Payment_id (FK)

Customer_id (FK)

---------------------------------------------------



Admin Table : To  Manage interface for the restaurants to receive and manage the customer's orders.

          Admin_id (PK)

          Customer_id (FK)

            Order_id (FK)

            Food_id (FK)

            Supplier_id (FK)

            Payment_id (FK)  

          Employee_id (FK)



----------------------------------------------------

 

 

Login Table: Add new users to the application and allow access using Customer id and Password.

            Customer Id (FK)

            Admin Id(FK)

            Password
