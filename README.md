#MADE BY MIRO HAGELBERG

This is the repository of Software Development Skills: Full-stack coursework. The code for tasklist and the project are stored in separate folders within this repository.

Learning diary and video of the code runthrough can be found in Documents-folder. The tasklist and the project repositories both include the exact same source code that is found in this repository. The separate repositories can be found from the following URLs:

Tasklist: https://github.com/Hageli/fullstack_tasklist

Project: https://github.com/Hageli/fullstack_project

#RUNNING THE PROJECT:

1. Download the project files from this Github repository or the separate one linked above.
2. Rename the .env_temp file into .env and insert your MongoDB url into the MONGO_URL variable (.env_temp is found within the server folder)
3. Open the root folder of this project in terminal and run "npm run install-everything" (This should install all required node_modules in client, server, and root folder. In case this fails, navigate to each of the folders separately and run "npm install" )
4. After succesfully installing the node_modules, both the server and the client can be started within the root folder by running "npm run dev"
