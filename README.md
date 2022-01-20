# Lost Chapter

## Project Description

	Lost Chapter is the last online bookstore website you’ll need. Users can buy or rent
	books from various spans of published year, genre, categories, authors, and editions.
	The lost chapter offers books in hardcover, softcover, and even Ebooks. Users can register
	and create an account. 	Lost Chapter is attentive in their marketing and occasionally has
	sale and deal periods. Users can pay online for their books through the website.

    Users may also list their own items up for auction, and bid on other user’s items.
	On our welcome page, users will be able to see a list of featured items and items that currently
	have a sale. When purchasing items, users can select a quantity of items they would like.
	Additionally, admins may log in and mark certain items for sale. They may also post new products
	on the website for regular users to buy.

## Technologies Used

* Spring Framework
	- Spring Web
	- Spring Boot
	- Spring Data
	- Spring Test

* Testing
	- JUnit5
	- Mockito
	- JaCoCo
	- SonarCloud

* Frontend
	- Angular 2+
	- Bootstrap CSS Framework
	- Angular Material

## Features

### List of features ready:
* Login
* Register
* Cart
* Product Display
* Product Search
	* Quantity Select
* User Profile
* Sales/Deals
* Checkout
* Featured Products
* Dark Mode
* Notifications
	* TransactionKeeper in the backend

### TODOs for future development
* Reset Password
* Bidding/auctions
* Tech Support Chat
* Admin Sales Metrics Dashboard
* Flash Deals

### Improvement/s to be implemented
#### Signup Feature
* Automatic computation of age based on the user's birth date (This can be achieved either on the backend or frontend).
	* Age and Birth date can be removed as well as it doesn't really affect other features.
* Frontend-wise:
	* Removal of Role selection when creating a new account.
		* By default, it should be "Customer".
	* Removal of unnecessary field validation to create an account.
		* For example, you only need username, password, email, first and last name to access most of websites.
* Backend-wise:
	* Stronger password hashing
		* The current version of hashing the password stores the same hashed password
		* Example:
			* original password = "password"
			* hashed password = "A91FN10248H10A0N"
			* Users who used "password" as their password has the same hashed password value.

#### User Profile Feature
* Automatic computation of age based on the user's birth date (This can be achieved either on the backend or frontend).
	* Age and Birth date can be removed as well as it doesn't really affect other features.
* Frontend-wise:
	* Removal of the "Role" field
	* A functional changing of profile picture (This is more of a beautification of the application as it doesn't really affect the functionality of the app).
#### Cart Feature
* Frontend-wise:
	* Implementation of deleting all the books from the cart
	* A validation for the "Checkout" button in the cart, User shouldn't be able to proceed to "Checkout" page if there are no current books in the cart.
	* Correctly displaying of the price of the books
		* The price that should be displayed on the cart should be based on the book if it is on sale or not.
#### Notification (checkout-summary.component.html)
* Frontend-wise:
	* The "Continue Shopping" button redirects to the User's Cart instead of the homepage.

## Getting Started

Needs to clone backend and frontend repository to run project:
*  ```git clone git@github.com:Revature-LostChapter/LostChapter-Frontend.git``` or ```git clone https://github.com/Revature-LostChapter/LostChapter-Frontend.git``` (for frontend)
	* navigate to frontend folder
	* npm install inside frontend folder
	* ng serve --open (to run frontend angular project, will automatically open page with frontend application on localhost:4200)
* ``` git clone git@github.com:Revature-LostChapter/LostChapter-Backend.git```  or ```git clone https://github.com/Revature-LostChapter/LostChapter-Backend.git``` (for backend)
  * Run backend on IDE of your choice

> Be sure to include BOTH Windows and Unix command
> Be sure to mention if the commands only work on a specific platform (eg. AWS, GCP)

- All the `code` required to get started
- Images of what it should look like

## Usage

> Here, you instruct other people on how to use your project after they’ve installed it. This would also be a good place to include screenshots of your project in action.

## Contributors

- Alemu Robele
- Artemis Mills
- Ashli Oneal
- Allexa Hernandez
- Connor Huston
- Cory Hall
- Damilare Olaleye
- Danaya Chusuwan
- Jahlil James
- Jean Maurice
- Jim Michael
- Jymm Enriquez
- Kibru Kassa
- Leon Hakimi
- Mike Dingeldein
- Marshall Hobbs
- Rafael Dantas
- Tanveer Singh
- Willie Conaway

## License

This project uses the following license: [<license_name>](<link>).

## Documents
For holding things like team assignments, concepts, planning documents, etc.

## Document links
Test Plan Document: https://docs.google.com/document/d/1nGRJMu4LGTSjuZY0GUp_VLu81o1yDdfm1QTFWWccAk0/edit
Test Case Document/Traceability Matrix: https://docs.google.com/spreadsheets/d/1woF_-tgnZny2AWq9FqLeeP2inJDJtTSEbYzm2knazVM/edit#gid=0
