Explore-Odisha eCoomerce Website
    
- eCommerce platform built with the MERN stack & Redux.

## Features

- Full featured shopping cart
- Product reviews and ratings
- Top products carousel
- Product pagination
- Product search feature
- User profile with orders
- Admin product management
- Admin user management
- Admin Order details page
- Mark orders as delivered option
- Checkout process (shipping, payment method, etc)
- PayPal / credit card integration
- Database seeder (products & users)

## Build & Deploy

```
# Create frontend prod build
cd frontend
npm run build
```

There is a Heroku postbuild script, so if you push to Heroku, no need to build manually for deployment to Heroku

### Seed Database

You can use the following commands to seed the database with some sample users and products as well as destroy all data

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

demo@example.com (Customer)
demo

```

![Screenshot (206)](https://user-images.githubusercontent.com/56496307/118442498-4af31c80-b708-11eb-847a-0dd92823970b.png)
![Screenshot (208)](https://user-images.githubusercontent.com/56496307/118442518-50506700-b708-11eb-8320-87ef6f9bfcea.png)
![Screenshot (204)](https://user-images.githubusercontent.com/56496307/118442519-521a2a80-b708-11eb-8128-b5b1bc08a2d3.png)
![Screenshot (181)](https://user-images.githubusercontent.com/56496307/118442535-59413880-b708-11eb-9537-48c3dfc7a21b.png)
![Screenshot (226)](https://user-images.githubusercontent.com/56496307/118442564-5fcfb000-b708-11eb-834c-074cebebc350.png)
![Screenshot (201)](https://user-images.githubusercontent.com/56496307/118442586-66f6be00-b708-11eb-82c8-f4c84a46831e.png)
