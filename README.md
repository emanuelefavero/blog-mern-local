# Blog MERN

This is the local optimized version of blog-mern. A MERN blog app from an assignment project from [the Odin Project](https://www.theodinproject.com/lessons/nodejs-blog-api). It is part of the full stack API section of their course.

## Test the app locally on your machine

- Clone the repo and `cd` into the project directory
- Add a _.env_ file in the root directory with the following variables:

```dotenv
MONGO_URI='YOUR_MONGODB_URI'
SECRET='ANY_SECRET_KEY'
PORT=4000
```

- Run:

```bash
cd backend
yarn install
yarn start
```

- Open a new terminal and run:

```bash
cd client
yarn install
yarn start
```

- Open [http://localhost:3000](http://localhost:3000) to view it in the browser.
