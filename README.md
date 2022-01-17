# ProShop eCommerce Platform

> eCommerce platform built with the MERN stack & Redux.

## Features

-   Top products carousel
-   Product pagination
-   Product search feature
  ![ecom1](https://user-images.githubusercontent.com/53987404/149725732-393469da-8b5e-4acc-833b-8480c0ad33ee.PNG)
  
-   Full featured shopping cart
-   User profile with orders

![ecom4](https://user-images.githubusercontent.com/53987404/149726316-644675a8-51fa-4277-9a3b-825633721126.PNG)
-   Product reviews and ratings
![ecom2](https://user-images.githubusercontent.com/53987404/149726240-44f8ce52-3e02-4b01-8a43-c4317a1c8c2c.PNG)

-   Checkout process (shipping, payment method, etc)
![ecom7](https://user-images.githubusercontent.com/53987404/149726614-63b428a4-7b01-4fa7-bb28-14e38c324231.PNG)
-   PayPal / credit card integration
![ecom8](https://user-images.githubusercontent.com/53987404/149726934-acb3ee5b-1450-45f5-8d07-cab60834b1c8.PNG)

-   Admin product management
-   Admin user management
-   Admin Order details page
-   Mark orders as delivered option
![ecom9](https://user-images.githubusercontent.com/53987404/149726770-b44131d7-21ad-412a-914e-23a0ba49e8b4.PNG)
![ecom10](https://user-images.githubusercontent.com/53987404/149726776-48de8ab0-85f3-4ed2-9d03-4995165fea2c.PNG)
![ecom11](https://user-images.githubusercontent.com/53987404/149726780-a0767a4d-6050-440a-aac0-7e1edd75edf5.PNG)
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
