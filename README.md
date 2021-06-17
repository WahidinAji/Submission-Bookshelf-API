## setup
 - npm install
## running
 - npm run start-dev

 1. Using Hapi framework
 2. using ESLint for code-style
 3. using nodemon for run-watch
 4. install joi for required : src docs `@hapi`

 # books.js
  - array books
  - export books
 # server.js 
   * CRUD
     - import modul hapi 
     - create server port, host and cors
 # routes.js
   * postData
   * getAllData
   * getDataById
   * editDataById
 # handler.js
   * post
     - define attribute
     - create id by `nanoid()`
     - validation name can't be null
     - validation readPage can't biggest than pageCount
     - if ! success send response 500 server error
   * getAllData
   * getDataById
     - success send data (id founded)
     - fail send null array of data (id not founded)
   * editDataById
     - define attribute by Id
     - update attribute finished fi readPage === pageCount
     - validation name can't be null
     - validation readPage can't biggest than pageCount
     - if id can' find it, send response 404 id was not found
   * deleteDataById
 # postman
   * all checklist