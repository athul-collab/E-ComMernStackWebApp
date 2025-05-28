# E-ComMernStackWebApp

# How to Setup & Run this Project

❖ Install NodeJs ( Ignore If Already Installed )
    1. Visit the official Node.js website https://nodejs.org/en/download/
    2. Download the Node.js installer
    3. Run the installer.

— First Run Server then Client —
❖ Steps to setup Server of the project

1. Open Project Folder In VS Code

2. Setup The MongoDB & obtain MongoURI

    Link : https://www.mongodb.com/cloud/atlas/register
    Add mongoDB URI in “ .env ” file of server folder

3. Setup Cloudinary
    Link : https://cloudinary.com/users/register_free
    Add Cloudinary Keys ( cloud name, secret key, api key ) in “ .env ” file of
    server folder

4. Open server Folder in Integrated Terminal

5. Install Dependencies Using Command

    npm install

6. Now Run Project Using Command

    npm run server

    Note: Before Running Client Projects make sure Server is Running

❖ Steps To Run Client of The Project

1. Open client Folder in Integrated Terminal

2. Install Dependencies Using Command
    npm install

3. Now Run Project Using Command
    npm run dev
