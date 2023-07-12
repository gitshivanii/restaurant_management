### Steps to Install:

Clone Repository to your local drive
From your favorite terminal enter 
`$ cd restaurant_management`
Run to install packages
`$ npm install` 
`$ cd client`
Run to install React packages
`$ npm install` 
`$ cd ..`
To run the app.
`$ npm start`


## API Routes

### /checks
#### GET Routes
 * /checks  returns JSON of all 'checks' entries
 * /checks/paid returns JSON of all paid checks
 * /checks/unpaid returns JSON of all unpaid checks
 * /checks/:id returns single check by ID
#### POST Routes
 * /checks/seat creates a new 'check' or a new gues seating, returns json with ID data
#### PUT Routes
 * /checks/:id Updates check by ID
#### DELETE Routes
 * /checks/delete/:id

### /menu
#### GET Routes
 * /menu returns JSON of all menu entries
 * /menu/:section returns JSON of all menu entries by section / category
#### POST Routes
 * /menu/add Creates a new menu entry, returns JSON with ID
#### DELETE Routes
 * /menu/:id Deletes a menu entry by ID

### /order
#### GET Routes
 * /order returns JSON of all order entries
 * /order/paid returns JSON of all paid checks
 * /order/unpaid returns JSON of all unpaid checks
 * /order/:id returns single check by ID / category
#### PUT Routes
 * /order/:id Updates check by ID

### /servers
#### GET Routes
 * /servers returns JSON of all waitstaff entries
 * /servers/:code Validates the user access code
#### POST Routes
 * /servers/add Creates a new waitstaff/server entry, returns JSON with ID 
