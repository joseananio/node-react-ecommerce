This is a fork!

## About
In this project, we want to create an ecommerce store similar to amazon but moreso, like jiji.com.gh.  
We focus more on categories like Amazon, but give more freedom to users like jiji.  
- Any user should be able to view any published product
- Any user should be able to post products
- Users will be veriried in the future
- Companies will become specialized users in the future, like amazon

## Set up

### 1. Clone repo

```
$ git clone git@github.com:joseananio/node-react-ecommerce.git
$ cd node-react-ecommerce
```

### 2. Install MongoDB

Download it from here: https://docs.mongodb.com/manual/administration/install-community/

### 3. Run Backend

```
$ yarn install
$ yarn start
```

### 4. Run Frontend

```
# open new terminal
$ cd frontend
$ yarn install
$ yarn start
```

### 5. Create Admin User

- Run this on the browser: http://localhost:5000/api/users/createadmin
- It returns admin email and password

### 6. Login

- Go to http://localhost:3000/signin
- Enter admin email and password and click signin

### 7. Create Products

- Run http://localhost:3000/products
- Click create product and enter product info

## Collaboration
- Tickets will be used to distribute tasks
