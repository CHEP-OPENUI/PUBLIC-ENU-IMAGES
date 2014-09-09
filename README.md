PUBLIC-ENU-IMAGES
=================

To store images

Repository to store css files

Make sure you change your folder to PUBLIC/ENU/IMAGES on your local. Open this folder on MS web matrix. Then, add this remote rep and do a pull to get latest changes.

****If you want to overwrite all your local changes from server then, use below commands.

For example, you have added this remote rep with name: IMAGE_FILES.

Now, on webmatrix, open shell and paste below commands.

git fetch IMAGE_FILES 
git reset --hard IMAGE_FILES/master 
git clean -f -d
