CLI is a fast easy was to navigate through your PC like a pro.
If you want to add a new file to your projec Locally (that you will eventually push to HitHub to have a back up)
follow these steps.
-navigate to the parent directory (yes it is the same thing as a folder) with you files you cloned from Git.
    -type "pwd" to know where you are currently in your file system.
    -type "ls" to list the files in that directory. Do they look familiar? If not uses your GUI to look around if you need help while learning.
    - type "cd /home/user/GitRepo" here cd means change directory and each level in the directory is seperated by a "/".
                If you use your GUI you can locate the desired folder and right click it, go to "properties" and there you can see the filepath. Does it match what you typed? If so press enter and you are in the directory you need to be in.
-To create a new file simply type "touch name_of_file.extension"
    -Here "touch" enables file creation ability, name_of_file is exactly as it sounds whatever name you want your file to have and ".extension" is the type of file you are creating. recall that so far we have created .HTML .CSS .JS and .MD files. There are many types of files and you can learn more here. [File extension library](https://www.computerhope.com/issues/ch001789.htm)
If you have installed [Visual Studio Code](https://code.visualstudio.com/) you can open your new file by doing the following.
-press the up arrow until you see your previous command...
    -do you see your last command? "touch name_of_file.extension"
-use the arrow to go back to and delete "touch"
now type "code" and leave a space between that and the file name
-press enter and your file will open in "VS Code".
-As an alternative if younwant to open all files in a directory to VS Code type "code ."