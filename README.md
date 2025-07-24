Instructions for react application:
-------------------------------------
1. Download the react zip file i.e rbac zip file
2. Extract the rbac folder and open in visual studio code
3. Open terminal and run "npm install" command in terminal
4. "Nodemodule" folder will be create after "npm install" command
5. Install these packages in the terminal. "npm install bootstrap", "npm install axios" , "npm install react-router-dom"
6. Now run the application using "npm start" command. Application ui will be opened on the browser
7. A login page will be opened on the browser
8. You can create user along with the role(Admin, Editor, Viewer) in the signup page.
9. Admin can have all the right to create, update, read
10. Editor can have access update, read pages
11. Viewer can open read pages only
12. Role authentication is given to the pages. So pages can be opened based on the user role


Instructions for API application:
-------------------------------------
1. Download the core web api application zip folder and extract folder.
2. Open api application, build the solution.
3. Run below commands one by one in "package manager console" after build succeeded.
   add-migration 'init'
   update-database
   A migration folder will be generate in solution after run "add-migration" command.
   Databse will be generate along with all the tables after run "update-database" command.
4. Now build the solution and run the application
5. Swagger page will be opened after successfully run the application
6. Now you can do your operations on the swagger.
7. First register a user along with role name.
