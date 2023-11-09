# Image_DB_work_ch2
In simple words, within this repo, we have a codebase related to store image into DB , manage width refinement and then fetch data from DB and perform  desired operations. 


As per the attached  csv file which contains image data referenced by the column depth. The rest of the 
columns (200) represent image pixel values from 0 to 255 at each depth.

The challenge consists of the following requirements:
• The image size is relatively big. Therefore, there is a need to resize the image width to 150 
instead of 200.
• The resized image has to be stored in a database.
• An API is required to request image frames based on depth_min and depth_max.
• Apply a custom color map to the generated frames.
• The solution should be based in Python.
• Containerize the solution.


Here, dependencies are available in requirement.txt.
Within each module of code handle separate working.
the main file handles all the execute along with fast API.

The application runs on port 8005.

