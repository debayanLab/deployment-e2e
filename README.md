# e2e-serverside

Run the following commands to build server
~~~
npm install
npm run build
npm run seed
nodemon start
~~~

In case the database still has the previous users' names, type `mongo` in shell and type following
~~~
use dev_DB
db.user.drop()
~~~

Close the shell, then run `npm run seed` again to seed the database. This should work.

Citation: https://github.com/VertikaJain/node-express-ts-chat-app
