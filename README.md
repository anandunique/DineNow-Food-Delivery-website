# DineNow - Food Delivery Website Based on MERN Stack

## Description
DineNow is a food delivery web application built with the MERN stack. It allows users to browse various menus, filter food items, add items to their cart, proceed to payment, and place orders. Users can also view their orders and access an admin page to manage displayed items and orders.

### Table of Contents
1. [All About the Project](#all-about-the-project)
2. [Installation and How to Run the Project](#installation-and-how-to-run-the-project)

## 1. All About the Project

### 1.1 Home Page

   
  ![image](https://github.com/user-attachments/assets/020f7df0-73bd-49dc-9d2b-4e4aa158326a)<br></br>

### 1.2. Home Page containing food items available with Menu Filtering abilities.<br></br>

  ![image](https://github.com/user-attachments/assets/687780b8-6ab2-4485-afd4-a86f970ef8cf)<br></br>


### 1.3. The Footer of the website remains same for Contact information.<br></br>

   
   ![image](https://github.com/user-attachments/assets/f3bea942-56eb-45d0-b8bb-f9faa03e3810)<br></br>
   

### 1.4. Users should Login/SignUp before placing Orders.<br></br>

   
   ![image](https://github.com/user-attachments/assets/03d8104f-0fa8-4484-a0fc-5a051cef7f62)<br></br>

   

### 1.5. After signing in, users can add items to cart.<br></br>


   ![image](https://github.com/user-attachments/assets/929acf81-d13b-447f-8915-37906f7a59ef)<br></br>
   

### 1.6. In the Navbar , Click the Cart page and give "Proceed to CheckOut".<br></br>


   ![image](https://github.com/user-attachments/assets/312cc199-3f22-46a4-85f2-0bd40887320f)<br></br>
   

### 1.7. After this, Enter the details and if clicked "Payment on Delivery" The website directs user to 'MyOrders' page (or)
###   "Stripe(Debit/credit" option leads to Payment page integrated with Stripe API.<br></br>


   ![image](https://github.com/user-attachments/assets/7a2f5cf4-8cab-4c2d-b129-40998fb4de60)<br></br>
   

### 1.8. The Stripe API integrated payment portal is opened and the specific Card Information for specified
###   country can be copied from Stripe API website.<br></br>
   

   ![image](https://github.com/user-attachments/assets/b3c524a3-e474-4598-9365-6611bbe3f812)<br></br>
   

### 1.9. After payment, 'MyOrders' Page is opened.<br></br>


   ![image](https://github.com/user-attachments/assets/25d7b9f0-43f6-41ae-9617-d339c783a435)<br></br>
   

### 1.10. This is the Admin Page where we can add new Items, List items that should be displayed in the website,
###    and manage Orders by users.<br></br>

  ![image](https://github.com/user-attachments/assets/e0722519-34af-4fef-b39b-f6b690345e3e)<br></br>

## 2. Installation

### Prerequisites

Make sure you have the following installed on your system:
- Node.js
- npm (Node package manager)
- MongoDB(or use mongodb Atlas account)

## Steps To Setup Backend Of The Project
1. Open Project Folder In VS Code
2. Open Integrated Terminal
- Right Click on Sidebar > Select “Open In Integrated
Terminal”
3. Type “npm install” and press Enter and Wait for
Installation to be completed (requires Internet)
4. Setup The MongoDB database and paste the connection string in .env file
5. Also get the JWT private key, Stripe API private key form Stripe API website and paste in .env
  <img width="683" alt="image" src="https://github.com/user-attachments/assets/28c14e8d-8ca6-4bcd-b50f-33d76fed09f9">

6. Type "npm run server" to run the backend and check in the console if printed "DB connected".

## Steps to run Frontend/Admin
1. Similarly open admin/Frontend in seperate integrated terminals by "cd folder".
2. Type "npm i" to install all the necessary packages
3. Type "npm run dev" in the terminal.






  



