# Evo-Scheduling
A developed AI algorithm to schedule practices upto 18 choreographers (not fool-proof) designating each choreographer a 1-hour practice timeslot based on their weekly availability.

For future Evo Board use:

# OPENING UP THE TERMINAL

1. On MacOS (Press Command + Space and search "Terminal")
2. On Windows (Press Windows button and search "Powershell")

The terminal should now look like: 

# MACOS TERMINAL

![Screenshot 2024-01-07 at 4 36 30 PM](https://github.com/Johnrev16/Evo-Scheduling/assets/76535774/26b982fe-8180-4950-8166-9e542490f607)

# WINDOWS TERMINAL 

![PICTURE](https://github.com/Johnrev16/Evo-Scheduling/assets/94932129/f0ed625c-4dda-476b-80b3-2e004053b784)


# PRE-PRE-STEPS

1. Open your Terminal, and type and enter: "javac -version"

If "javac is not recognized," or if your JDK version is not 18.0 or above, please proceed to Steps 2-4.

2. Download the most recent Java JDK version using this link: [https://www.oracle.com/java/technologies/downloads/] Choose the version that's compatible on your device (Windows, MacOS) and select the x64 installer, or x64 DMG Installer. Click and open the downloaded file to install the most recent Java JDK version. 

3. Exit your current Terminal.
   
4. Open up a new Terminal, and check again your JDK version by typing and entering: "javac -version"

# PRE-STEPS

1. Create a folder in your Desktop to store all the .java and .csv files.
2. Download the Choreographer Conflicts Google sheets in the Board folder as a .csv file. Rename the .csv file to something easy to type (e.g. fall-22)

![Screenshot 2024-01-07 at 4 32 14 PM](https://github.com/Johnrev16/Evo-Scheduling/assets/76535774/a04a578d-e775-4607-9eef-5c5121f377eb)


# STEPS

1. Download all the .java files in this GitHub repository named "Choreographer," "Arc," and "Main" and store them inside your folder.
2. Open up your terminal.
3. In the MacOS terminal, type and enter "cd Desktop/name_of_folder" -- so if your folder is named "evo-scheduling," you should type "cd Desktop/evo-scheduling"
4. In the Windows terminal, type and enter "cd OneDrive/Desktop/name_of_folder" -- so if your folder is named "evo-scheduling," you should type "cd OneDrive/Desktop/evo-scheduling"
5. Now that you're in the correct directory, you can now run the program!

# RUNNING THE PROGRAM

1. On MacOS and Windows, type and enter "javac Main.java" to compile the .java into a .class
2. Then, type and enter "java Main" This should prompt you to choose the .csv file. Type that file name.
3. This should prompt a second question to choose which algorithm to run. Type and enter "1".
4. If algorithm 1 does not INITIALLY provide a valid assignment, re-run step 2-3 with the first algorithm at least THREE TIMES. I
5. If that still does not work, type and enter "2" to run the second algorithm.
6. If neither algorithm works, good luck! (do it by handdd)

If a valid assignment has been created, feel free to share this draft schedule to the choreographers and change any times that would fit best. 
   

