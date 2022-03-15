# Homework 2 #
##### *Due March 30th, 2022* #####
After painstakingly going through installation, setup, and your git intro, you have finally set your IDE up. It only gets easier from here.
For your first real Data Science assignment, you will be exploring the first two steps of the Data Science pipeline, Collection and Processing. You will have two weeks to do this, as I am giving you the break to relax.

### Step 0: Setup ###
To begin your setup, run these following commands in your Terminal.
1. ```cd src``` to go to source directory.
2. ```cd Tamid-TechEdu-S22``` to cd into the class repository.
3. ```code .``` to open VSCode. Use the VSCode terminal for these next commands.
4. ```git pull``` to update the repository with the Week 3 folder and the Week 3 code.
5. ```cd Week3``` to be in the Week 3 folder.

### Step 1: Create Your Database ###
Make a database, and it can contain WHATEVER data you want!! Make sure it has at least 5 elements (5 index children indexed 0-4 with at least 2 of its own child nodes in there).
Now, go on [Firebase](https://firebase.google.com/) and sign in with your gmail account (personal preferred).
1. Click "Get Started".
2. Go to the **Realtime Database** tab.
3. Click the plus next to the dbname-default-rtdb cell to make a child node, which would be the title of your parent node. DBname will be the name of 
4. Use the plus on the parent node to make your index children.
5. Use the plus on your index nodes to add values to the Database.

Add whatever data you want, preferrably with Name, Value, and whatever other categories you would like.

### Step 2: Integrating Your DB With Code ###
With your database done, export it as a JSON file and move the JSON file to the same folder you are coding in. You should see it in the left tab of VSCode afterwards.

**Import the JSON File into your program, convert it to CSV, then make a DataFrame out of it. Print the dataframe, get the summary statistics, and access a column.**
This code should not be bad at all, you can get it straight from the slides and the Week 3 Code file.

### Step 3: Submission ###
I will be adding an extra step to submission to ensure that it doesn't fail on your end.
1. Run ```git pull``` to ensure your git is up to date. MAKE SURE YOUR FILES ARE SAVED.
2. Run ```git add name-week3.ipynb``` (same naming convention as usual).
3. Run ```git add filename.json``` so I can see your database contents.
4. Run ```git commit -m "Enter message here like last time"``` to commit your changes.
5. Lastly, run ```git push``` and that will push your file onto the repo!

Slack Sam or I if you have any questions. Good luck, and get it done before 3/30. No excuses this time!
