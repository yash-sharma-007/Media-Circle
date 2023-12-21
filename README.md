# FullStack Media-Circle App

## Technologies Used

- **Frontend:**
  - React.js
  - Material-UI
  - Redux

- **Backend:**
  - Node.js
  - Express.js
  - MongoDB

## Getting Started

This is an example of how you setting up project locally.
To get a local copy up and running follow these simple steps.

### Prerequisites


* npm
  ```sh
  npm install npm@latest -g
  ```

### Installation

1. Get a MongoDB Atlas Application connection URL at [https://www.mongodb.com/home](https://www.mongodb.com/home) by creating the database.
2. Clone the repo
   ```sh
   git clone https://github.com/yash-sharma-007/Media-Circle.git
   ```
3. Install NPM packages
   ```sh
   cd client
   npm install

   cd server
   npm install
   ```
4. Create `.env` file and put MongoDB url in `.env in server directory`
   ```js
    MONGO_URL = ENTER YOUR MONGO URL (without inverted commas);
   JWT_SECRET = ENTER YOUR SECRET 
   ```
5. Run  following command in terminal inside client directory
   ```sh
   npm start
   ```
6. Run  following command in terminal inside server directory
   ```sh
   nodemon server.js
   ```
<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- USAGE EXAMPLES -->
## Usage

Now you can test your url on your browser url
 ```js
   http://localhost:3000/
   ```
Server is running on 5000 PORT
