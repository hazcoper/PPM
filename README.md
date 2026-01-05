# PPM
Personal-Photo-Manager


The main idea behind this project is to create a system to host my pictures

I have used google photos in the past. It is pretty close to what I am trying to achieve. It is still missing a couple of features, but by far the biggest reason i do not want to use it is because of the cost.

Immich and photoprism are good alternatives. But in my experience they are quite slow and do not offer all the features that I want


I want to make a simple system that is as fast as possible. It will not be designed for multiple users, it will be designed for a single user.
It will eventually have a front end that will allow to view all the photos and to search them. Then it will have multiple scripts that will allow you to mange the photos (tag, search for duplicates...). The frontend will allow simple management operations like deleting (eventaully rotating, editing the tags...)

The system will consist of a folder where all the images will be stored. Then there will be a database. The database is what will allow for fast searching

The folder will be organized by year/month/day. Each image will have a unique id. The unique id will be used to reference the image in the database
Each image will have its own thumbnail as well.

These is the information that I want to be searchable:
    - date
    - location
    - tags (these will be generated automatically with some ai model)
    - people (these will be generated automatically with some ai model)
    - camera model
    - other exif data
    - custom notes (these will be added manually by the user)
    - folders (these will be manually created by the user to represent some trip for example)


