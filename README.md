# Unbound

Developed with Unreal Engine 4

To clone for use in Unreal Engine:

1) Make an empty folder (anywhere, you can do it on your desktop if convenient)
2) In the folder, open cmd or gitbash and run:

       git init
     
       git remote add origin https://github.com/kevprakash/Unbound.git
     
       git pull origin master

3) Once you do that, use Dynamic Locomotion (from the asset store) to make a new 4.23 project
4) Close Unreal
5) Copy all the files from the intial folder you made into your project folder, overriding all files when asked
6) Open up the project and go to "Source Control" -> Set the type to Git and hit accept

IMPORTANT: DO NOT ADD OR COMMIT FROM CMD ONLY USE THE EDITOR TO ADD AND COMMIT CHANGES. You have to push from cmd though.

DO NOT add or commit files that were not changed from the base. In general, if there is a "?" on the asset and it's not in the "MyStuff" folder, do not add or commit it.

If you experience an error when pulling and it says you have uncommited changes, DO NOT commit/stash the files. Just delete those files and pull the latest version.
