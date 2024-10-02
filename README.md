
# Mini CRM System

A simple web application designed to manage company information efficiently. The system allows users to create and view company details using a full-stack architecture with Next.js for both the frontend and backend, and MongoDB for the database. The Mini CRM System implements essential CRUD (Create and Read) functionalities.

## Project Overview and Objectives

The objective of this project is to develop a user-friendly CRM (Customer Relationship Management) system that allows companies to store, manage, and view their business information. The primary goal is to simplify company management using a full-stack approach with modern web technologies.

## Technologies Used

- **Frontend**: Next.js, React
- **Backend**: Next.js, Node.js
- **Database**: MongoDB

## Installation Steps

To set up the Mini CRM System locally, follow these steps:

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/parash156/mini-crm-system.git
   cd your-repo-name
   ```

2. **Install Dependencies**:
   ```bash
   npm install
   ```

3. **Set Up Environment Variables**:
   Create a `.env` file in the root of your project and add the following variables:
   ```plaintext
   MONGODB_URI=your_mongodb_connection_string
   ```

4. **Run the Application**:
   ```bash
   npm run dev
   ```

5. **Access the Application**:  
   Open your web browser and navigate to [http://localhost:3000](http://localhost:3000).

## API Endpoints and Purpose

### Create Company

- **Method**: `POST`
- **Endpoint**: `/companies`
- **Request Body**:
  ```json
  {
    "name": "Company Name",
    "industry": "Industry Type",
    "description": "Description of the company."
  }
  ```
- **Response**: The newly created company object.

### Get Company

- **Method**: `GET`
- **Endpoint**: `/companies/:id`
- **Response**: The requested company object.

