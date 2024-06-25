# Blog Management Backend Service

This Node.js project is a backend service for a Blog Management Platform, providing essential functionalities for user management and blog post management. It utilizes Express.js, Bcryptjs, Jsonwebtoken, and Mongoose for efficient development.

Base url: https://admin-api-nwkl.onrender.com/

## Functionalities

#### 1. User Management:

- Sign up a new account
- Sign in with username and password
- Get specific user details

#### 2. Blog Post Management:

- Create a new blog post
- Get all blog posts
- Get a specific blog post
- Update a specific blog post
- Delete a specific blog post

## API Endpoints

#### User Management

| Methods | Urls                | Actions                               |
| ------- | ------------------- | ------------------------------------- |
| POST    | /api/auth/sign-up   | Sign up a new user account.           |
| POST    | /api/auth/sign-in:  | Sign in with a username and password. |
| GET     | /api/auth/{userId}: | Get specific user details.            |

#### Blog Post Management

| Methods | Urls                 | Actions                      |
| ------- | -------------------- | ---------------------------- |
| POST    | /api/posts:          | Create a new blog post.      |
| GET     | /api/posts:          | Get all blog posts.          |
| GET     | /api/posts/{postId}: | Get a specific blog post.    |
| PATCH   | /api/posts/{postId}: | Update a specific blog post. |
| DELETE  | /api/posts/{postId}: | Delete a specific blog post. |

## Technology Stack

- Express.js: A web application framework for Node.js.
- Bcryptjs: A library for hashing and salting passwords.
- Jsonwebtoken: A library for creating JSON Web Tokens for user authentication.
- Mongoose: An ODM (Object Data Modeling) library for MongoDB.

## How to Run

Follow these steps to run the project locally:

#### 1. Clone this repository.

```bash
git clone https://github.com/manishtmtmt/admin-api.git
```
#### 2. Navigate to the project folder using your command line interface.

```bash
cd admin-api
```

#### 3. Install the project dependencies by running the following command:

```bash
npm install
```

#### 4. Start the development server with:

```bash
npm run dev
```
## Documentation

The project is documented with Swagger, providing detailed information about the available endpoints and their usage. You can access the Swagger documentation by visiting `/api-docs` when the server is running.