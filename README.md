# Dev-Diary a Full-Stack Web Application created using Node.js, Express.js and MongoDB 
## Features of Dev-Diary 
### For Creators:
     It has Admin panel where the Creator can Register using Username and Password.
     To access Admin Panel they can Sign In using their Credentials.
     Once Signed In they can Create New Blog post, Edit already created post and delete it.
### For Readers:
     They can View the Blogs posted by the Admin.
     Has a search bar where they can search blogs using keywords.
     
## You Need
      NodeJS
      Database MongoDB Cluster
## Create .env File
### Inside .env use the MongoDB url to store the data (Sample Below)
    MONGODB_URI=mongodb+srv://<username>:<password>@clusterName.xxxxxxx.mongodb.net/blog
    JWT_SECRET=MySecretBlog
## Installation 
### To install and run this project - install dependencies using npm and then start your server:
     npm i 
     npm run dev 
