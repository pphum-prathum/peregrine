To start the server for the website Peregrine, there are a few steps that must be taken:

Step 1: Create two new terminals.
In one terminal, change the directory into the front-end folder by typing “cd sec3_gr8_fe_src”.
Similarly, change the directory of the other terminal to the back-end folder by typing “cd sec3_gr8_ws_src”.

Step 2: Running the code will require some additional modules; therefore, installing dependencies is necessary. 
In the terminal for “sec3_gr8_fe_src”, run the command: npm install express, nodemon, dotenv.
In the terminal for “sec3_gr8_ws_src”, run the command: npm install express, nodemon, dotenv, mysql2, cors.

Step 3: Setup a database user by creating a .env file in the folder “sec3_gr8_ws_src”.
The user set in the file will also need to be granted privileges in the “Users and Privileges” tab in MySQL.

Step 4: Run the command "npm start" in the both terminal, then open the browser and navigate to "localhost:3030" to access the website.

---------------------

*There is an ERROR in the admin_edit.html file*