                    WELCOME TO JIDI ELECTRONICS !!


For our final CodeNation project we were placed in teams and were given the task of creating an electronics store.

In my team were Jenny, Izzy, Diwa and myself Ian, so I named the store JIDI Electronics.

The store comprised of a front-end store front hosted on Heroku connected to a separate back-end database created in MS-SQL and hosted on a Microsoft Azure Database, with tables for ‘customers’ who had registered with the store for an account, a stock database, a list of orders plus a table of customers who were presently logged in.

Customers who bought items were given a unique order reference (utilising the date and time in JS), their passwords were hashed in the database using bcrypt and each person logging in had a unique session ID which permitted them to log in for 2 hours until their session terminated and were automatically logged out.

