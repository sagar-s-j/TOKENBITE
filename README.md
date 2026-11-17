# Skip the Queue

**Order ahead at any hotel or restaurant, pay online, and collect with a token. No crowd, no waiting.**

Skip the Queue is a web platform where any hotel, restaurant, café or canteen can register, publish its menu and manage orders, and where customers can search for a place, order in advance and pick up their food using a token number.

## The problem

Hotels and restaurants of every size struggle when it gets crowded. Customers stand in queues, wait without knowing how long, and often find out an item is unavailable only after waiting or paying. Staff are overwhelmed taking orders by hand, which leads to missed and wrong orders.

## The solution

A single platform that moves ordering and payment to the customer's phone and gives hotels a live dashboard to handle rush hours calmly.

## Features

**For customers**
- Search hotels by name, city or cuisine, and filter by cuisine
- Browse each hotel's live menu and build a cart
- Sign up and log in with name, phone number and password
- Choose a payment method and get a unique token number
- Live order status on the token screen, including a clear message when an item is unavailable but the rest of the order can still be collected

**For hotels and restaurants**
- Register a hotel in minutes
- Owner dashboard with live orders and stats (orders, preparing, completed, revenue)
- Complete or reject each order
- Tap an item inside an order to mark it unavailable, so the customer can still collect everything else
- Menu stock switches to mark an item sold out for all customers instantly

## Tech stack

- HTML, CSS and vanilla JavaScript (single `index.html`, no build step)
- Browser `localStorage` as the data store for this prototype
- Deployed as a static site on Vercel

## Run locally

Open `index.html` in any modern browser. No installation needed.

## Demo

- **Customer:** create an account on the sign-up screen, pick a hotel and place an order
- **Hotel owner:** log in with `demo@hotel.com` / `Demo@123` to manage orders for the sample hotel "Spice Route Kitchen", or register your own hotel

Place an order as a customer, then open the owner dashboard in the same browser to see it arrive.

## Deploy on Vercel

1. Push this repository to GitHub
2. On vercel.com, click **Add New > Project** and import the repository
3. Set Framework Preset to **Other** and leave build settings empty
4. Click **Deploy**

Every push to the main branch redeploys the site automatically.

## Current limitations

- Data is stored in each browser, so an order placed on one device does not appear on another device
- Passwords are stored in plain text in the browser and payments are simulated, so this is a prototype and not ready for real customers
- Sample hotels are demo data

## Roadmap

- Shared cloud database so customers and hotels connect across devices
- Secure authentication with hashed passwords
- Real payment gateway integration
- Hotel menu editor with prices, photos and categories
- Order notifications by SMS or push
- Maps and nearby hotel search
- Ratings and reviews

## Origin

This project began as a canteen ordering system for the Alvas Institute of Engineering & Technology (AIET) as part of an innovation design thinking project, and grew into a platform for hotels and restaurants everywhere.

## Author

Built by sagar s.
