# NINJA MARKET _(MERN Stack E-Commerce Project)_

## Overview

This is a full-stack e-commerce web application built using the MERN (MongoDB, Express, React, Node.js) stack. It is designed to provide a seamless shopping experience for users, with features such as product listings, shopping cart functionality, user authentication, and more.

### Features

- User authentication (signup, login, logout)
- Browse and search for products
- Add products to the shopping cart
- Manage the shopping cart (add, remove, update quantities)
- Checkout and place orders
- View order history
- Admin panel for managing products and orders

## Getting Started

Follow these instructions to get the project up and running on your local machine for development and testing purposes.

### Prerequisites

- Node.js and npm installed on your machine
- MongoDB installed and running
- Stripe API keys (for payment processing)

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/mohammednudman/NinjaMarket.git
   cd NinjaMarket/backend 
   npm install 
   cd .. 
   cd frontend
   npm install
   ```
### Create a .env file in the server directory and configure environment variables:
```.dotenv
PORT=8000
DB_URI =
STRIPE_API_KEY=
STRIPE_SECRET_KEY=
JWT_SECRET=
JWT_EXPIRE=
COOKIE_EXPIRE=
SMPT_SERVICE =
SMPT_MAIL=
SMPT_PASSWORD=
SMPT_HOST=
SMPT_PORT=
```

### License
This project is licensed under the MIT License - see the LICENSE.md file for details.

Contact
If you have any questions or need further assistance, please feel free to contact us at [mohammednudman@gmail.com](mohammednudman@gmail.com).