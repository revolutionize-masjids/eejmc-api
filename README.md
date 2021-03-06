# EEJMC Back End

## How do I run this on my machine?

### Pre-requisites

Make sure you have Node, MongoDB, and Yarn installed

```bash
  # MAC OSX (using Homebrew)
  brew install node
  brew install yarn
  brew install mongodb

  # Windows (using Chocolatey)
  choco install node
  choco install yarn
  choco install mongodb
```

### Run MongoDB

Make sure you read the documentations on how to install MongoDB. And also make sure you can run the `mongod` command

```bash
  # start a mongodb service, normally on http://localhost:27017/
  mongod
```

### Run it!

Run the server on your machine

```bash
  git clone https://github.com/revolutionize-masjids/eejmc-back-end.git
  cd eejmc-back-end

  # install dependencies and run the dev server
  yarn install
  yarn run dev
```

### Recommended downloads

- MongoDB Compass (will make managing the MongoDB database easier with a GUI)
- Postman (test API with HTTP requests)
- Atom (awesome editor that the rest of the team is using)

## Stack

- JavaScript ES8
- Node.js
- Express.js
- MongoDB
- Mongoose
- GraphQL
- Apollo
- Firebase
