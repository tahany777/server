# Server App

```javascript
npm install body-parser cors express mongoose nodemon

//start server 
* nodemon index.js


// you should specify the route after the cors
app.use(cors());
app.use('/posts', postRoutes);
```

## Hide .env file in GitHub

```javaScript
git rm -r --cached .
git add .
git commit -m ".gitignore is now working"
```

### create .env file

```javaScript
npm i dotenv
//create new file named .env
//create new file named .env.example
//create .gitignore file using gitignore.io
//push it to github
```

### Login With Google (JWT)

```bash
npm install bcryptjs jsonwebtoken
```