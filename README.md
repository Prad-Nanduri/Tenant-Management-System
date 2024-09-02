****
# Real Estate Rental and Tenant Management System 
![Rental Management System](https://github.com/user-attachments/assets/c2004ab6-4f02-44a9-83ec-8e9b98465be9)

Full-stack real estate rental and tenant management system. A web application that allows two types of USERS to use the application. The two types of users are the OWNER and the TENANT.

The owner can post a property for rent, manage tenants, register rent payment, and create a property contract.
The tenant can search and filter properties, view property details, send an email to the owner of the property, and use the built-in chat application for communication between the owner and the tenant.


## Features

- Post a property for rent
- Search and filter properties
- View property details
- Built-in Chat Application for communication between owner and tenant
- Secure JWT authentication using access and refresh tokens
- Send emails between owner and tenant
- Create Property Contract
- Manage tenants
- Register Rent Payment

## Configuration and Installation Instructions


- Node.js
- React.js
- Tailwind CSS
- Vue.js
- npm
- MongoDB
- Cloudinary
- Ethereal Email


1. Install the required packages for the backend:

```bash
$ cd server
$ npm install
```

2. Open a new terminal session and install the required packages for the frontend:

```bash
$ cd client
$ npm install
```

3. Configure the environment variables inside the server folder:

```bash

- create a .env file and add the following variables:
- generate secret keys for jwt tokens using online tools

MONGO_URI= <your_mongo_uri>
ACCESS_TOKEN_SECRET_OWNER= <your_access_token_secret_owner>
ACCESS_TOKEN_SECRET_TENANT= <your_access_token_secret_tenant>
REFRESH_TOKEN_SECRET_OWNER= <your_refresh_token_secret_owner>
REFRESH_TOKEN_SECRET_TENANT= <your_refresh_token_secret_tenant>
ACCESS_LIFETIME=15m
REFRESH_LIFETIME=7d
CLOUDINARY_CLOUD_NAME=<your_cloudinary_cloud_name>
CLOUDINARY_API_KEY= <your_cloudinary_api_key>
CLOUDINARY_API_SECRET= <your_cloudinary_api_secret>
RESET_PASSWORD_KEY= <your_reset_password_key>
EMAIL_VERIFICATION_KEY= <your_email_verification_key>
CLIENT_URL=http://localhost:3000
EMAIL_HOST=smtp.gmail.com
EMAIL_PORT=587
EMAIL_USER= <your_gmail_address>
EMAIL_PASS= <your_gmail_pass> or <your_gmail_app_password>

```

4. Configure the environment variables inside the client folder:

```bash

- create a .env.local file and add the following variables:

VITE_APP_BASE_URL=http://localhost:3000
VITE_APP_API_URL=http://localhost:5000/api
VITE_APP_API_HOST=http://localhost:5000
```

5. Run the application:

```bash
$ cd server
$ npm run dev
```
****
