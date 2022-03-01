# Homework 1 #
##### *Due March 9th, 2022* #####
Once again, congratulations on making it into Tamid Tech! Upon your acceptance, as well as pulling this repository, you are now a member of the Spring 2022 Tamid Tech Edu class! This is your first homework assignment. There will not be any real work due next Wednesday, but this is just so I know your IDE is set up.

### Step 1: Setting Up the Repo with Terminal ###
First, we need to make sure your repository is setup. I have provided the instructions on the slides, but I will provide them here as well.

1. Go to your designated terminal, and cd to the folder you want your repository to be in. (```cd src``` is recommended. If src is not a directory in your User folder, you can run ```mkdir src``` and then cd to it.)
2. Type in ```git clone https://github.com/mananbhatt5/Tamid-TechEdu-S22.git```. This will create a new folder containing all of the class materials.
3. Run ```cd Tamid-TechEdu-S22```, and this will put you into the new folder.
4. Run ```cd Week1``` and you will be in the folder for this week.
5. Run ```code .``` and VSCode will open up with this folder. You should see the Week 1 Code.ipynb file containing all the examples from class in there, as well as the README.md file you are reading right now. 

If VSCode is not installed on your machine, follow the instructions [here](https://code.visualstudio.com/download) and download accordingly.

### Step 2: The Homework Itself
Now here are the assignment requirements.

1. Create a new file titled name-week1.ipynb, where name is obviously your credentials.
2. In this file, import your necessary libraries for reading dataframes.
3. Download a dataset off of [Kaggle](https://www.kaggle.com/) and move that to your Week 1 folder. **DO NOT USE THE SAME DATASET THAT I USE, OR IT WILL INDICATE THAT YOU ARE NOT PUTTING IN ANY EFFORT FOR THIS CLASS!**
4. Read it in as a CSV file, then make a dataframe out of it.
5. Print out the head of the dataframe.
6. Show the summary statistics from the dataframe.
7. Access a column from the dataframe.

Once you follow all of these steps, you are done! Now you just have to submit the file.

### Step 3: Submitting The Files ###
This is the final step of the homework!

1. Do ```git add filename.ipynb``` and ```git add filename.csv``` where both the filenames represent your ipynb and CSV files, respectively. This will add them to the git server.
2. Do ```git commit -m "Type a short message, like 'Pushing changes for Homework 1' here."```. This will provide a message onto the repository along with your filenames.
3. And finally, do ```git push```. This SHOULD upload the files onto the github repository. I know git likes to be finnicky sometimes, so if you are having issues, let Sam or I know!
TIP: You can use ```git status``` to check which of your files have been added and which haven't.
