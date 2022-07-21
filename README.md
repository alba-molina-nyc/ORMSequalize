### install dependencies

1. npm install sequelize pg pg-hstore
2. npm install sequelize -g sequelize-cli
3. sequelize init initialize sequelize in our project

### Directions

1. open config.json -> add your info
   from
   {
   "development": {
   "username": albamolina,
   "password": null,
   "database": "database_development",
   "host": "127.0.0.1",
   "dialect": "mysql"
   },

to -> {
"development": {
"username": "albamolina",  
 "password":,
"database": "orm_tutorial",
"host": "127.0.0.1",
"dialect": "postgres"
},

sequelize -> to get all commands you can use in sequelize

2. create and connect to db through cli
