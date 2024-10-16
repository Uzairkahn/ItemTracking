
                                              Item Tracking Program

Overview
The Item Tracking Program is designed to help the Corner Grocer efficiently manage and analyze item purchase data. By processing text records, the program provides insights into the frequency of items purchased and generates a visual histogram representation of this data.

 Features
Check frequency of an item: Input an item name to retrieve its purchase frequency.
Display all item frequencies: View a complete list of items and their purchase frequencies.
Display item histogram: Generate a histogram using asterisks to visualize item frequencies.
Exit the program: Safely exit the application.

 Requirements
C++ Compiler: Ensure you have a C++ compiler installed (e.g., g++, clang++).
C++ Standard Library: This program uses features from the C++ Standard Library.

 File Structure
The main source code for the item tracking program.
CS210_Project_Three_Input_File.txt: The input file containing the purchase records. Ensure this file is in the same directory as projectThree.cpp.
frequency.dat: The output file where frequency data is saved (automatically created by the program).

Instructions for Running the Program

1.Setup Environment: 
  Ensure you have a working C++ compiler installed on your system.
   Place projectThree.cpp and CS210_Project_Three_Input_File.txt in the same directory.

2. Compile the Program:
   Open a terminal or command prompt and navigate to the directory where your files are located. Compile the program using the following command:

  g++ projectThree.cpp -o projectThree

   This will generate an executable named    projectThree
3. Run the Program:
   Execute the program by entering the following command:
   projectThree
  
4. Interacting with the Program:
   - Follow the on-screen menu prompts to check the frequency of an item, display all item frequencies, or visualize the histogram.
   - Input your choice based on the menu options displayed.
   - If you wish to exit the program, select the exit option

Example Usage
Here’s how a typical session may look:

Menu:
1. Check frequency of an item
2. Display all item frequencies
3. Display item histogram
4. Exit
Enter your choice: 1
Enter item to check frequency: apple
apple frequency: 5
Menu:
1. Check frequency of an item
2. Display all item frequencies
3. Display item histogram
4. Exit
Enter your choice: 3
apple     *****
banana    ***
orange    ********
Menu:
1. Check frequency of an item
2. Display all item frequencies
3. Display item histogram
4. Exit
Enter your choice: 4
Exiting program.


 Output
The program creates a backup file named `frequency.dat`, containing the frequencies of each item processed from the input file. This file can be used for further analysis if needed.
 Troubleshooting
File Not Found Error: If the program cannot find the input file, ensure that CS210_Project_Three_Input_File.txt is present in the same directory as projectThree.cpp
Compilation Errors: Ensure your compiler supports C++11 or later. If you encounter errors, double-check your code for typos.

Conclusion
This program effectively assists the Corner Grocer in managing their produce section by providing data-driven insights into purchasing trends. Your feedback is welcome to improve its functionality further.

