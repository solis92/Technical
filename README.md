Clone Repository
Execute the SQL script, it will create the required tables
Then execute the debugger with F5 you should see the swagger display

http://localhost:5159/api/News/{elements}



There are some screenshots to guide the process

Well to avoid performance issues all the callbacks are asynchronous
Furthermore I though a way to avoid to consult many times the same id from the hacker API
Using SQL I create a row for the first time that any id is consumed
Using this method the number of petitions to the API got reduced drastically


