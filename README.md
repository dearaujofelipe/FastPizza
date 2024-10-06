Fast Pizza requirements:

- simple app where users can order one or more pizzas from a menu.
- no user accounts and no login.
- the menu can change so it should be loaded from an API that is already working.
- cart for the pizzas.
- order requires name, phone number and address.
- users should mark their order as priority for 20% additional cart price.
- orders are made by sending a POST request with the order data to the API.
- no payment processing, payment is made on delivery
- each order will get a unique ID so user can late look up their order.
- users should be able mark their order priority even after the order has been placed.

Fast Pizza Features + pages:

- feature categories

  - User
  - Menu
  - Cart
  - Order

- pages
  - Homepage '/'
  - Pizza menu '/menu'
  - Card '/cart'
  - Placing new order '/order/new'
  - looking up an order '/order/:orderID'

State Management:

- User, global UI state
- Menu, global remote state
- Cart, global UI state
- Order, global remote state

Stack:

- React
- tailwindcss
- Redux
- React Router
