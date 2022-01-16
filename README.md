# ProShop eCommerce Platform

> eCommerce platform built with the MERN stack & Redux.

## Features

-   Full featured shopping cart
-   Product reviews and ratings
-   Top products carousel
-   Product pagination
-   Product search feature
-   User profile with orders
-   Admin product management
-   Admin user management
-   Admin Order details page
-   Mark orders as delivered option
-   Checkout process (shipping, payment method, etc)
-   PayPal / credit card integration
-   Database seeder (products & users)

### Env Variables

Create a .env file in then root and add the following

```
NODE_ENV = development
PORT = 5000
MONGO_URI = your mongodb uri
JWT_SECRET = 'abc123'
PAYPAL_CLIENT_ID = your paypal client id
```

### Install Dependencies (frontend & backend)

```
npm install
cd frontend
npm install
```

### Run

```
# Run frontend (:3000) & backend (:5000)
npm run dev

# Run backend only
npm run server
```

## Build & Deploy

```
# Create frontend prod build
cd frontend
npm run build
```

There is a Heroku postbuild script, so if you push to Heroku, no need to build
manually for deployment to Heroku

### Seed Database

You can use the following commands to seed the database with some sample users
and products as well as destroy all data

```
# Import data
npm run data:import

# Destroy data
npm run data:destroy
```

```
Sample User Logins

admin@example.com (Admin)
123456

john@example.com (Customer)
123456

jane@example.com (Customer)
123456
```

## License

The MIT License

Copyright (c) 2020 Traversy Media https://traversymedia.com

Permission is hereby granted, free of charge, to any person obtaining a copy of
this software and associated documentation files (the "Software"), to deal in
the Software without restriction, including without limitation the rights to
use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of
the Software, and to permit persons to whom the Software is furnished to do so,
subject to the following conditions:
