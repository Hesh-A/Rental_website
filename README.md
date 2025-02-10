# Rental_website

## Overview
A web application to search and filter rental houses in Australia. This project is built using Node.js, Express, MongoDB, and React.

## Features
- Search for rental properties by location, price, number of bedrooms, and property type.
- View detailed property information.
- Add, edit, and delete property listings (for admins).

## Getting Started
### Prerequisites
- Node.js and npm installed
- AWS DynamoDB

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/rental-website.git
   cd rental-website
   
## Using AWS DynamoDB

### Prerequisites
- AWS account

### Setup
1. Create a DynamoDB table:
   - Go to the DynamoDB service in the AWS Management Console.
   - Create a new table with the name `RentalProperties` and specify the primary key (ID).

2. Install AWS SDK:
   ```bash
   npm install aws-sdk
