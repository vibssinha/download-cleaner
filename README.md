# Download-Cleaner
After downloading so many things overtime I have a tendancy to have a really long download folder. I have created a file that cleans your downloads folder and organizes each of your files into different folders called 'Pictures' 'Videos' 'Documents' or 'Others' depending on their filetype.

DISCLAIMER: THIS CODE IS FOR SYSTEMS THAT RUN ON WINDOWS ONLY

DISCLAIMER: YOU CAN USE POWERSHELL IF YOU WOULD LIKE BUT MY DIRECTIONS ARE FOR CMD

Steps on using it:

Step 1: Make sure you have Python installed. You can check this by running the command 'python --version' in CMD. If it gives you an error, you need to install Python, if it returns your python version, you can move on to the next step.


Step 2: Make sure you know the name of your local drive whose download folder you want to clean, for most people it will probably be their 'C:'. Make sure you also know the username on that drive. You can check this by going into CMD. It should say 'C:\Users\Your_Username>'.


Step 3: When you download these files make sure to download them to your download directory and then move them to your directory that contains your downloads directory. After downloading these files, you can move these files by opening up a brand new CMD and running (Make sure you change "Your_Username" to your actual usename before running it and do not take double quotations off)

move "C:\Users\Your_Username\Downloads\DownloadCleaner.py" "C:\Users\Your_Username\DownloadCleaner.py" && move "C:\Users\Your_Username\Downloads\Files.py" "C:\Users\Your_Username\Files.py"


Step 4: Stay on the command line and run the command

python DownloadCleaner.py


Step 5: It will ask you for the name of the drive whose download folder you want to clean out, enter that. It will also ask for the username you use on that drive, enter that.


Step 6: Your download folder should be clean. Each file was put into folder called Videos, Pictures, Documents, or Others. If you find that a certain file is not where you expect it to be, check others


Step 7: If you encounter any kind of error make sure the drive and username are putting in is correct and run "python DownloadCleaner.py" again


Have a nice day
