# Sample Node.js & MongoDB Web Application
This is a Node.js web application based on "The Web Developer Bootcamp" by Colt Steele, with modifications and bug fixes. This application utilizes various technologies and packages, including:
- Node.js with Express for the web server
- Bootstrap for front-end design
- Mapbox for fancy cluster map 
- MongoDB Atlas as the database
- Authentication and Authorization with the passport package using a local strategy
- Cloudinary for cloud image storage
- Helmet for enhanced security
- ... 

To run this app, you will need to create accounts for Cloudinary and MongoDB Atlas and add a `.env` file (in same folder of app.js) with the following content:
```sh
CLOUDINARY_CLOUD_NAME=[Your_Cloudinary_Cloud_Name]
CLOUDINARY_KEY=[Your_Cloudinary_Key]
CLOUDINARY_SECRET=[Your_Cloudinary_Secret]
MAPBOX_TOKEN=[Your_Mapbox_Token]
DB_URL=[Your_MongoDB_Atlas_Connection_URL]
SECRET=[Your_Secret_Key] # anything you like
```
