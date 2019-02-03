# Let's Connect

A small social network called the 'LetsConnect' for developers. It has some common features such as adding profiles, writting posts and comments,...
The whole project is built using Nodejs/Express, React/Redux and MongoDB
Try the [live demo](https://whispering-headland-48836.herokuapp.com/)

## Getting Started
```
# Install dependencies for server
npm install

# Install dependencies for client
npm run client-install

# Run the client & server with concurrently
npm run dev

# Run the Express server only
npm run server

# Run the React client only
npm run client

# Server runs on http://localhost:5000 and client on http://localhost:3000
```

### Prerequisites
For development purpose, create new keys.dev.js file in config folder and then add your API or MongoDB URI connection strings
```
module.exports = {
  mongoURI: [MongoURI],
  secretOrKey: [secret key for JWT authentication]
};

```
Atlas MongoDB:
https://www.mongodb.com/cloud/atlas




## Authors

- **Jason Pham**


## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

