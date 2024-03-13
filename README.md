# Inviguard

### 1. Introduction https://github.com/anidaduharkic/Inviguard-issues/issues/2#issue-2183680634

Inviguard is an advanced Management Information System (MIS) application designed to optimise inventory operations effectively. It begins with a secure User Authentication system, ensuring that only authorised personnel can access the system’s functionalities. Those authorised personnel are the employer who manages the orders from the employees that make the orders. Later on, if there is no more material in the inventory ordered by the employees, then the employer orders the sufficient amount of material that is needed.


The centralised Dashboard provides users with a comprehensive overview of warehouse activities, including inventory levels, incoming and outgoing shipments, and performance metrics. With its robust features, the Management Information System enhances productivity and accuracy in warehouse operations.

### 2. Features https://github.com/anidaduharkic/Inviguard-issues/issues/6#issue-2183818577

The features that Inviguard contains are:

* User Authentication for Employee/Employer
* Profile of the User
* Inventory Management Interface (for suppliers add, update, delete cruds)
* Order Management Interface (creating the Order, accepting and processing it)
* Notification about the materials that are low in stock
* Qr Code Scanning

### 3. User Interface https://github.com/anidaduharkic/Inviguard-issues/issues/7#issue-2183823883

Inviguard includes the following pages:

* Home Page of the Company
* Registration Page for the authorised users
* Profile Page
* Dashboard Page
* Inventory Management Page
* Order Management Page
* QR Code Scanning Page

![alt text](https://github.com/anidaduharkic/Inviguard-issues/blob/5dcb5760b9e757d82b8ef7a545a382eab1f98a93/Inviguard-Sitemap.png "SiteMap")

### 4. Functionality 

#### 4. Home Page https://github.com/anidaduharkic/Inviguard-issues/issues/9#issue-2183861414

This is the landing page of this application.
It contains:

* The Company name along with the short description of it
* The 'Login' button that will lead to the User log in page

#### 4.1 Log in Page https://github.com/anidaduharkic/Inviguard-issues/issues/3#issue-2183715000

After the user presses the "Login" button on the homepage, the system navigates the user to the Login form of the page. This page must ensure that:

* only the authorized users have access to the system
* the right credentials are put in by the user
* After a successful login, the user is then navigated to the systems user profile page.

#### 4.2 Profile Page https://github.com/anidaduharkic/Inviguard-issues/issues/8#issue-2183857253

After the log in page a user will be redirected to its profile. 
Profile page contains: 

* The profile picture of the user
* The information about the user
* Log out button 
* On the side the user can navigate to the other pages

#### 4.3 Dashboard page https://github.com/anidaduharkic/Inviguard-issues/issues/4#issue-2183730572

The user can navigate to the dashboard page from the navigation menu. The dashboard page is the main page of the system where the main and most important information is presented for example:

* incoming orders
* orders for materials submitted by employees
* materials low in stock
* This information is beneficial for the users as it helps them in their decision-making process.

#### 4.4 Inventory Management Page https://github.com/anidaduharkic/Inviguard-issues/issues/5#issue-2183744459

In order to aquire the right information on the warehouse and the materials stored in it, the user navigates to the inventory page where the materials are listed in different categories along with the acording price, quantity and supplier. Also, the materials are provided with a code, name, description, picture and place where it is stored. The inventory page will also give the user the ability to enter new products to be stored and also update or delete existing ones.

#### 4.5 Order Management Page https://github.com/anidaduharkic/Inviguard-issues/issues/10#issue-2183882523

On the navigation bar the user can navigate ti the Order Management Page.
That page contains:

* Option to search for the orders
* List of the orders and its status
* Order details, update or cancellation of it
* Box to create a new order

#### 4.6 QR Code Scanning Page https://github.com/anidaduharkic/Inviguard-issues/issues/12#issue-2183983949

It can also be navigated to from the navigation bar and this page contains:

* Interface for scanning QR codes associated with products or orders.
* Feedback on successful scans and errors.

### 5. Technical Requirements https://github.com/anidaduharkic/Inviguard-issues/issues/11#issue-2183977619

The Management Information System is built using the following technologies:

Backend: Java, Spring, PostgreSQL
Frontend: Angular

### 6. Wireframes 

#### 6.1 Home Page 
![alt text](https://github.com/anidaduharkic/Inviguard-issues/blob/b8b6caebf2089e72e0a034419f256d7fd09db4eb/Home%20page.png "HomePage")

#### 6.2 Login Page 
![alt text](https://github.com/anidaduharkic/Inviguard-issues/blob/72a6a22911822da81e56b6472cddb6a1d0ecc895/Log%20in%20Page%20.png "LoginPage")

#### 6.3 Profile Page 
![alt text](https://github.com/anidaduharkic/Inviguard-issues/blob/72a6a22911822da81e56b6472cddb6a1d0ecc895/Profile%20Page.png "ProfilePage")

#### 6.4 Dashboard Page 
![alt text](https://github.com/anidaduharkic/Inviguard-issues/blob/72a6a22911822da81e56b6472cddb6a1d0ecc895/Dashboard.png "DashboardPage")

#### 6.5 Inventory Management Page
![alt text](https://github.com/anidaduharkic/Inviguard-issues/blob/72a6a22911822da81e56b6472cddb6a1d0ecc895/Inventory%20page.png "InventoryPage") 

#### 6.6 Order Management Page 
![alt text](https://github.com/anidaduharkic/Inviguard-issues/blob/72a6a22911822da81e56b6472cddb6a1d0ecc895/Orders%20page.png "OrderPage") 

#### 6.7 QR Code Scanning Page 
![alt text](https://github.com/anidaduharkic/Inviguard-issues/blob/72a6a22911822da81e56b6472cddb6a1d0ecc895/QR%20page.png "QrCodePage")















