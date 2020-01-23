# POSDB

#### Dependencies:
Internet connection 
Node.js 0.10.x

Run the following commands:

Extract the zip file with project in it or git clone this repository, open up a terminal or powershell
`cd posdb`
`npm install`

*If anything goes wrong* here are some additional command you can use with out harm:

`npm install sqlite3`

`npm install connect-sqlite3`

`npm install express-session`

This should be the command neccessary to download the dependencies for the proj:

To start:
`npm start`

Now browse to *localhost:3000* to play with the app

If there is any issues when starting, try to npm install <missing dependency>

Accounts you may play with:

|username |  password  | role								 |
|---------|------------|-------------------------------------|
|charlie1 |  password  | admin (super user) - prefered login |
|johnny3  |  password  | employee							 |
|john2    |  password  | manager							 |
|sally4   |  password  | accountant - only sales data        |

To update data, usually clicking the the row of data you want to update will 
spawn a pop up for you to edit
