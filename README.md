# Expense Tracker (NestJS & ReactJS)

This is expense tracker web application. It is built with NestJS (backend), ReactJS (frontend) and MySQL (database). It had used some popular library like React-Toastify (message alert), dnd-kit (drag and drop), React Query (manage the API calling) and Chart.js.


## Features

1. Manage expense and income and the same time
2. User can create multiple wallets
3. View the expense/income distribution by pie chart, bar chart and line chart.



### Steps

1. Pull [MySQL image](https://hub.docker.com/_/mysql)
2. Start the container and create database (You may need to create a user in the MySQL container)
3. Create a .env file as .env.example and fill them all  
4. Build the client folder (frontend)

    ```npm run build:client```
5. Start the application

    ```npm run start```
