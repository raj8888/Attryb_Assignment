# BUYC

## Features:
- Registeration/Login
- Authentication
- Hash Password
- JWT token
- Add Car


# Backend

## Tech Stack:
**NPM Modules:** Express.js,Mongoose.js,Bcrypt,dotenv,Jsonwebtoken.

**Database:** MongoDB.

## For Running Locally:
- clone the project
```bash
https://github.com/raj8888/Attryb_Assignment
```

- Go to the Repo
```bash
cd Attryb_Assignment
```

- For install Modules
```bash
npm i 
```

- For install nodemon globally
```bash
- npm i -g nodemon
```

- For start server
```bash
nodemon index.js
```

## Enviromental Varibles:

`MongoURL`

`PORT`

`seckey`

## API Refference

### For Users

- For User Register
```http
POST/api/register
```


- For User Login
```http
POST/api/login
```

- For add the new inventory
```http
POST/api/inventory
```


- For get the inventory
```http
GET/api/inventory
```


- For particular the inventory
```http
GET/api/inventory/:id
```


- For edit the inventory
```http
PATCH/api/inventory/:id
```

- For delete the inventory
```http
DELETE/api/inventory/:id
```


- For search the specifications
```http
GET/api/getspecs
```


## Backend Deployed Link (Sample)

[https://fair-erin-agouti-coat.cyclic.app](https://fair-erin-agouti-coat.cyclic.app)



# Frontend

## Tech Stack:
- HTML, CSS, React.js, JavaScript, Chakra UI, Redux UI.

- Live Demo: [https://buy-cars-company.netlify.app/](https://buy-cars-company.netlify.app/)
