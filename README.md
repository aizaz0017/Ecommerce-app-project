# Ecommerce-app-project

- Tech: Nextjs 13, Next Auth 4
- UI: Tailwind, chart.js, react-chartjs
- DB: MongoDB, Mongoose
- Payment: PayPal, Stripe


## Resources
- Source Code   :  https://github.com/aizaz0017/Ecommerce-app-project



## Run Locally

1. Clone repo

   ```shell
    $ git@github.com:aizaz0017/Ecommerce-app-project.git
   ```


2. Setup MongoDB

   - Local MongoDB
   - Install it from [here](https://www.mongodb.com/try/download/community)
   - In .env file update MONGODB_URI=mongodb://localhost/ecomapp

4. Install and Run

   ```shell
     npm install
     npm run dev
   ```

5. Seed Data

   - Run this on browser: http://localhost:5000/api/seed
   - It returns admin email and password and 6 sample products

6. Admin Login

   - Run http://localhost:3000/login
   - Enter admin email and password and click Login