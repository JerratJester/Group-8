## USER 
| Property      | Type | Default | Nullable | Relationship | Notes |
| ----------- | -----------|----------- | ----------- | ----------- | ----------- |
|userID |Primary key, int, identity | | |Relate to Order.userID, Shopping_Cart.userID | |
|username |varchar(30) | | | | |
|password |varchar(30) | | | | |
|FirstName |varchar(20) | | | | |
|LastName |varchar(20) | | | | |
|address |varchar(40) | | | | |
|city |varchar(20) | | | | |
|state |varchar(10) | | | | |
|zip |int | | | | |
|email |varchar(30) | | | | |
|phone |bigint | | | | |
|creditCardNo |bigint | | | | |
|isAdmin |boolean |'False' | | | |
|cartID |Foreign key, int | | |Relate to Shopping_Cart.cartID | |

## SHOPPING_CART
| Property      | Type | Default | Nullable | Relationship | Notes |
| ----------- | -----------|----------- | ----------- | ----------- | ----------- |
|cartID |Primary key, int, identity | | |Relate to User.cartID, Cart_Item.cartID | |
|amountOfItems |int | | | | |
|subtotal |decimal(10, 2) | | | | |
|tax |decimal(10, 2) | | | | |
|grandTotal |decimal(10, 2) | | | | |
|shippingType |varchar(20) | | | | |
|shippingCost |decimal(10, 2) | | | | |

## CART_ITEM
| Property      | Type | Default | Nullable | Relationship | Notes |
| ----------- | -----------|----------- | ----------- | ----------- | ----------- |
|cartID |Primary key, Foreign key, int, identity | | |Relate to Shopping_Cart.cartID |Composite primary key along with bookID |
|bookID |Primary key, Foreign key, int, identity | | |Relate to Book.bookID |Composite primary key along with cartID|
|itemPosition |int | | | | |
|price |decimal(10, 2) | | | | |

## BOOK
| Property      | Type | Default | Nullable | Relationship | Notes |
| ----------- | -----------|----------- | ----------- | ----------- | ----------- |
|bookID |Primary key, int, identity | | |Relate to Cart_Item.bookID | |
|name |varchar(60) | | | | |
|author(s) |varchar(75) | | | | |
|price |decimal(10, 2) | | | | |
|description |varchar(max) | | | |Holds the description of the book |
|hasBeenSold |boolean |'False' | | |Keeps track of whether or not the book has been sold to a customer or not |
|orderID |Foreign key, int | |Yes |Relate to Order.orderID |Keeps track of the order that a sold book is associated with |

## ORDER
| Property      | Type | Default | Nullable | Relationship | Notes |
| ----------- | -----------|----------- | ----------- | ----------- | ----------- |
|orderID |Primary key, int, identity | | |Relate to Book.orderID |Identifier for every complete order made |
|dateAndTime |datetime | | | | |
|userID |Foreign key, int | | |Relate to User.userID | |
|email |varchar(30) | | | | |
|phone |bigint | | | | |
|shippingType |varchar(20) | | | | |
|shippingCost |decimal(10, 2) | | | | |
|amountOfItems |int | | | | |
|subtotal |decimal(10, 2) | | | | |
|tax |decimal(10, 2) | | | | |
|grandTotal |decimal(10, 2) | | | | |
|FirstName |varchar(20) | | | | |
|LastName |varchar(20) | | | | |
|address |varchar(40) | | | | |
|city |varchar(20) | | | | |
|state |varchar(10) | | | | |
|zip |int | | | | |
