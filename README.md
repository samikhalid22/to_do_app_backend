# to_do_app_backend
This project contains code for backend of to_do_app. (Incomplete)

## For Windows 10
To run this web application follow the below steps

1.	[Download](https://nodejs.org/en/download/) and run Node.js installer

2.	[Download](https://www.postgresql.org/download/) and run PostgreSQL installer
      
            When installer prompts to enter password, enter: root
      
3.	Open pgAdmin from Start or Search
4.	Go to Servers > PostgreSQL > Databases
            
            When prompted to enter password enter: root
      
5.	Right click on Databases
6.	Select Create > Database…
7.	In Database field enter to_do
8.	Click on Save
9.	Download or pull [to_do_app](https://github.com/samikhalid22/to_do_app) & [to_do_app_backend](https://github.com/samikhalid22/to_do_app_backend) from GitHub
10.	Open cmd 
11.	Open to_do_app_backend and copy the directory path
12.	In cmd type “cd “ and paste the path. Press Enter
13.	Run npm install
14.	Run npx sequelize-cli db:migrate
15.	Run npm start
            
            Enter 'ctrl + C' to close
            
16.	Open another cmd window
17.	Open to_do_app and copy the directory path
18.	In cmd type “'cd '“ and paste the path. Press Enter
19.	Run npm install
20.	Run npm start
