**Activity Title:** Discovering Andhra Pradesh through Unix Commands

**Objective:** To introduce basic Unix commands in a fun and engaging way, by exploring famous locations in Andhra Pradesh.

**Prerequisites:** Git-SCM must be installed on your windows machine. No prior Unix experience needed.

**Activity Steps:**

1. **Introduction and Terminal Launch:**
   - Start by opening the Git-Bash on your computer.
2. **Start at the right place:**
   - Navigate to your "IT Essentials" Folder using `cd` command.
   - Create a new directory named `week07` using `mkdir week07`.

3. **Creating Andhra Pradesh Directory:**
   - Create a new directory named `AndhraPradesh` using `mkdir AndhraPradesh`.
   - Navigate into this directory using `cd AndhraPradesh`.

5. **Exploring Cities:**
   - Inside `AndhraPradesh`, create directories for different cities using `mkdir`. For example, `mkdir Amaravati`, `mkdir Visakhapatnam`, `mkdir Tirupati`.
   - Navigate into these directories using `cd` and back using `cd ..`.

5. **Learning about Cities:**
   - In each city's directory, create a text file named `about.txt` using `touch about.txt`.
   - Add interesting facts about each city into their respective `about.txt` files. For example, use `echo "Amaravati is the legislative capital of Andhra Pradesh." > Amaravati/about.txt`.

6. **Discovering Tourist Spots:**
   - Inside each city directory, create a sub-directory named `TouristSpots`.
   - In `TouristSpots`, create text files for different tourist locations. For example, in `Visakhapatnam/TouristSpots`, create a file `Beaches.txt`.

7. **Adding Information:**
   - Add details to each tourist spot file. For instance, `echo "Rushikonda Beach is known for its golden sands." > Visakhapatnam/TouristSpots/Beaches.txt`.

8. **Navigating and Exploring:**
   - Use `ls`, `cd`, and `cat` to navigate through the directories and read the contents of the files.

9. **Cleanup:**
   - Practice deleting files and directories with `rm` and `rmdir`.

**Reflection:**
Reflect on what they learned about Unix commands and how they relate to navigating through different directories, akin to exploring various cities and places in Andhra Pradesh.
