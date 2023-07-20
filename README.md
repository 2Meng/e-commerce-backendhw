# e-commerce-backend

# Description
The main reason I created this project was to explore the relationships of SQL-oriented datbases and how they interact with typical CRUD operations. By using the popular format of an e-commerce website, I was able to experience its real-world application. I wanted to be able to better understand how relational databases work, and this project helped me understand one-to-one, one-to-many, and other relational concepts. Completing this project also gave me more experience with routes.

This project can be used by a company that wants to compete in the online shopping market. With the back-end completed, a company can spend more time on building an attractive front-end website.

# USER STORY

AS A manager at an internet retail company I WANT a back end for my e-commerce website that uses the latest technologies SO THAT my company can compete with other e-commerce companies

# Table of Contents
Installation
Usage
Installation
To install, clone repo.

Make sure you have a .env file in the project. If not, create one and make sure it has the following information within:

DB_NAME="ecommerce_db" DB_USER="<your mysql username>" DB_PASSWORD="<your mysql password>"

If you do not already have it, download an API client like Insomnia REST client. You can get it here: https://insomnia.rest/

Usage
Open the terminal from the root folder. Then, run npm install to make sure you have all the necessary node modules. Next, run mysql -u root -p and enter your mysql password. Enter source .db/schema.sql, then exit mysql by entering either quit or exit Seed the database with npm run seed. Start the server with npm start

Now, open Insomnia REST client and put http://localhost:3001/ into the search bar. If you try a route that doesn't have an endpoint, the server will return 'Wrong Route!' First, try a GET route like http://localhost:3001/api/categories. This will return JSON data for all the categories. Try the other routes too! If you want to POST or PUT, make sure it is the correct format. To DELETE, you only need the ID of the item you are trying to delete on the particular route.

Video walkthrough: 


https://github.com/2Meng/e-commerce-backendhw/assets/91503750/0beb09c4-b3aa-4ccb-940e-9bed4e5fe554

