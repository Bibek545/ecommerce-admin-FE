# Ecommerce Admin Frontend

A modern, responsive React-based frontend interface for administrators to manage an e-commerce platform.

## ✨ Features

-   **Admin Authentication**: Secure login and session management using JWT.
-   **RESTful APIs**: Integration with a backend for all operations.
-   **CRUD Operations**: Full Create, Read, Update, and Delete functionality for managing products, orders, and users.
-   **File Management**: Upload and manage product images using AWS S3 Bucket.

## 🛠️ Tech Stack

-   **Frontend Library**: React
-   **Language**: JavaScript (ES6)
-   **Styling**: Bootstrap, CSS
-   **State Management**: React Context API / React Hooks
-   **HTTP Client**: Axios / Fetch API
-   **Authentication**: JSON Web Tokens (JWT)
-   **Database**: MongoDB (via backend API)
-   **File Storage**: AWS S3 Bucket
-   **Package Manager**: NPM

## 🚀 Getting Started

Follow these instructions to get a copy of the project up and running on your local machine.

### Prerequisites

Make sure you have the following installed on your machine:
-   Node.js (v14 or higher)
-   NPM (usually comes with Node.js)

### Installation & Setup

1.  **Clone the repository**
    ```bash
    git clone https://github.com/manojadh57/ecommerce-admin-FE.git
    cd ecommerce-admin-FE
    ```

2.  **Install dependencies**
    ```bash
    npm install
    ```

3.  **Environment Setup**
    Copy the example environment file:
    ```bash
    cp .env.example .env
    ```
    Edit the `.env` file and add your actual configuration values.

4.  **Start the development server**
    ```bash
    npm start
    ```
    The application will open in your browser on `http://localhost:3000`.

## ⚙️ Environment Variables

Create a `.env` file in the root directory based on the provided `.env.example`. The following variables are typically required:

```env
REACT_APP_API_BASE_URL=your_backend_api_base_url
REACT_APP_AWS_ACCESS_KEY_ID=your_aws_access_key
REACT_APP_AWS_SECRET_ACCESS_KEY=your_aws_secret_key
REACT_APP_AWS_S3_BUCKET_NAME=your_s3_bucket_name
REACT_APP_AWS_REGION=your_aws_region
REACT_APP_JWT_SECRET=your_jwt_secret
