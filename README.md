#middlewares

1- type is app level
  app.use((req,res,next) => {console.log} next();)
  app.use ((err,req,res,next) => {console.log} next();)

2- route level
  const md1=(req,res,next) => {..........} next();
  then we use md1 in middle of route within app.get.........

3- built in middlewares
  app.use(express.json()) like body-parser it gives us to access req.body
  
