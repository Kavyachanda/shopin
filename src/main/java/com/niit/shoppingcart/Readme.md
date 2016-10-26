Config
- ApplicationContextConfig.java :It is a configuration class which Contains datasource information and hibernate configuration.

###Controllers 
 All the classes are annotated with @Controller so that they can be scanned by spring MVC
 -	Productcontroller :  Contains MVC controller methods for admin Product CRUD operations.
 -	Suppliercontroller : Contains MVC controller methods for admin Supplier CRUD operations.
 -	Categorycontroller : Contains MVC controller methods for admin Category CRUD operations.
 -	Cartcontroller : MVC controller methods for user Cart functions.
 -	Homecontroller : MVC controller method for landing page.
 - Registercontroller : MVC controller methods for login and registration.
 - CheckoutHandler : MVC controller methods for payments using webflow.
 
 
###Models
 Contains all model classes.These models will be scanned by hibernate, so as to facilitate easy data manipulation using Hibernate ORM.
 -   Product.java
 -   Category.java
 -   Supplier.java
 -   Cart.java
 -   User.java
 -   Checkout.java
 
###DAO 
 Contains all DAO interfaces and DAOImpls containing RAW persistence Logic. 
 - ProductDAO.java
 - ProductDAOImpl.java
 - CategoryDAO.java
 - CategoryDAOImpl.java
 - SupplierDAO.java
 - SupplierDAOImpl.java
 - CartDAO.java
 - CartDAOImpl.java
 - UserDAO.java
 - UserDAOImpl.java
 - CheckoutDAO.java
 - CheckoutDAOImpl.java
