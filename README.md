Hi there! This is an API to view, add, modify and delete stores with endpoints using flask, sqlalchemy, flask-jwt & more.

These stores has items in it, emulating like a real life company accounting their stocks.

## Learning features
- Creating endpoints to create a new store and using the "name" in the dictionary.
- Using the "name" key to obtain the store name and items that were previously posted.
- When we reset the development server, all information using the post method is reset and gone.
- instead of using the key "name", we would like to use the unique id's, so we don't need to reiterate all the names in the dictionary. 

## Learning Docker
- Containers reuses' linux kernels(controls the hardware) rather than depending on another whole virtual machine using more resources
- This means its much quicker 
- Docker containers are based on 'images", snapshot of source code, libraries and depenencies. 