# Customers

## Register and Log In T8E-1

- Self-Register T8SR-1 (T=Team, 8=Group Num, S=Story R=Reg.)
- A Register Feature is a Must-Have Feature
- Estimated Effort: 3 days
- Self-registration is a functional requirement.
- A process that allows users to create their own accounts on a website or application

## Login T8SR-2

- A login feature is a Must-Have feature
- Estimated effort for a 4-person team to implement a self-register feature is 4 days to a week
- The system must allow users to authenticate using a username and password. So, it is a functional feature
- Allows users to access a secure system or application by entering their username and password.

## Username and Password Verification T8SR-3

- Username and password verification is a Must-Have priority for any website
- Estimated Effort: 1 Day
- This is a functional feature
- The process of comparing a user's entered username and password against the credentials stored in a database.

## Main Page T8E-2

## Inventory/Book Search and Matching T8SM-1

- This is a Must-Have feature for our customer
- Estimated effort could be as high as 2 days.
- This is a Functional Feature
- A process of finding items in an inventory database based on a description or name of the item.

## Show Inventory T8SM-2

- This is a must-have feature
- Estimated effort will take 3 days
- This is a functional Feature
- Users must see Inventory from highest to lowest And Inventory that match If Searched

## Shopping Cart and Pay Now T8E-3

### Pay Now UI T8SP-1

- This is a must-have feature
- Estimated effort to write a standard payment and process system should take 1 day
- This feature is a functional feature
- Will acquire customer Card Information, Shipping Speed, Address and Phone Number Then will move to Complete Order UI

### Delete Book from Cart T8SP-2

- This is a must-have Feature
- Estimated effort is 2 days for this feature
- This is a functional feature
- Feature allows customers to remove books from their shopping cart at any time before checkout.

### Remove User from Cart T8SP-3

- This is a must-have feature
- Estimated effort is 4 days
- This is a functional feature
- Must have a checkout button cannot click it if it's empty; do not open. If they remove all items in the cart, Kick customers back to the home screen

### Complete Order T8E-4

### Make a complete order Button T8SC-1

- This is a must-have feature
- Estimated effort for this feature is 4 to 5 days
- This is a functional feature
- Customer hit complete order show them and give them their receipt and Take items out of inventory and charge their card (By their Last Four Card Digits and Shipping address)

### Didn't Complete the order T8SC-2

- This is a must-have Feature
- Estimated effort is 6 hours for this feature
- This is a functional Feature
- If they do leave the items, they must stay in the cart. They can either go back to the checkout page or go to the main menu

### Confirmation page T8SC-3

- The priority is a must-have
- Estimated effort is 1 day
- This is a functional feature
- The Page will show their receipt. Will be able to click ok to exit receipt, cart will be empty and will not be able to go back on past screens. Once they Bought a book, remove it from the Databases and include it in sales report

# Admin

## Make Admin T8EA-1

- Give Customer admin T8SA-1
- This Requirement is a must-have feature
- Estimated effort to implement of this feature is 1 day
- This is a functional feature
- Admins can grant customer accounts admin privileges. This allows customers to perform certain administrative tasks, such as managing other users, creating and editing groups, and configuring system settings.

## Must make mock draft of the UI T8SA-2

- This is a must-have feature
- Estimated effort to create mockups is 3 days
- This Feature is non-functional
- UI designer created mockups of the UI for a new sale reporting system and Website, collaborating with the product team to ensure usability and aesthetics.

## Adjust Database T8EA-2

### Admin can Adjust Inventory T8SA-3

- This is a must-have feature
- Estimated effort to implement this feature is 2 days
- This is a functional Feature
- The admin can adjust inventory levels in the system. This includes adding new items, updating existing items, and deleting items.

### Admin can run Sales Report T8SA-4

- This is a must-have feature
- Estimated effort to implement this feature is 1 day
- This feature is a functional feature
- The administrator can generate a sales report that summarizes all sales data for a given period of time. The report can be generated in a variety of formats, including CSV

## Register and Log In T8EA-3

### Can't Self Register T8SA-5

- This is a must-have feature
- Estimated effort to implement this feature is 1 day
- This is a non-functional feature
- Admins cannot register themselves. This is a security feature to prevent unauthorized access to the admin dashboard.

### Log In T8SA-6

- This is a need-to-have feature
- Estimated effort to implement this feature is 1 day
- This is a functional feature
- To create an admin account, another admin must use the "Add New User" feature. Then will be able to successfully log in

# Database

## Inventory Database T8ED-1

### Inventory Item T8SD-1

- This is a must-have feature
- Estimated effort to implement this feature is 6 Hours
- This is non-functional
- Each inventory item needs a name, picture, price (Must Be formatted with dollars, commas, and must be stored as a Decimal), description, and an add to cart button

### Remove items from the Databases T8SD-2

- This is a must-have feature
- Estimated effort is 1 day
- This is a functional feature
- Database administrator removed unneeded items from the database to free up storage space. remove Items/books that are sold out

## Sales Report Database T8ED-2

### Turn A Sales Report to a CSV T8SD-3

- This is a must-have feature
- Estimated effort to implement this feature is 6 Hours
- This is non-functional
- The sales manager converted the sales report to a CSV file for the customer.