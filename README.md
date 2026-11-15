# Skip the Queue

Order food in advance, skip the queue, and collect with a token number.

Started as the ALVAS Institute of Engineering & Technology (AIET) canteen ordering system, built for an innovation design thinking project, and designed to grow into a platform for any hotel or restaurant.

## Features
- Student sign up and login with USN and password
- Menu by category, live cart, payment method selection
- Unique token number after payment
- Admin dashboard with live orders, search and filters
- Complete or reject orders, with a reason
- Item-level "Item Unavailable" flag: other items in the same order can still be collected

## Run locally
Open `index.html` in a browser. No install needed.

## Deploy on Vercel
1. Push this folder to a GitHub repository
2. Go to vercel.com, click **Add New > Project**, and import the repository
3. Framework Preset: **Other**. Leave the build command and output directory empty
4. Click **Deploy**

## Note
Data is stored in the browser (localStorage), so orders placed on one device are not visible on another. A shared database is the next step for a real multi-device launch.
