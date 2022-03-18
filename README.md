# Server App

```javascript
npm install body-parser cors express mongoose nodemon

//start server 
* nodemon index.js


// you should specify the route after the cors
app.use(cors());
app.use('/posts', postRoutes);
```