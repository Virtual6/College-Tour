# CS1D - Project-1

- Planning a trip:
3. Provide the capability to visit the initial 11 college campuses starting at University of California, Irvine (UCI).
a. Plan the trip starting at University of California, Irvine (UCI) then visit each of the other college campuses in the most efficient order (recursively choose the campus closest to the previous campus)
b. Display the total distance traveled

4. Offer the option to plan the shortest trip starting at University of Michigan
a. Obtain the number of college campuses to visit b. Visit the number of campuses specified (including University of Michigan) c. Plan the trip starting at University of Michigan then visit each of the other college campuses in the most efficient order (recursively choose the campus closest to the previous campus)
d. Display the total distance traveled e. Allow the college student to purchase multiple traditional souvenirs when visiting the college campuses

5. Offer the option to plan a custom trip
a. Allow a college student to select the starting college campus they wish to visit b. Then allow a college student to select all other college campuses they wish to visit c. Plan the trip starting with the selected campus then visit each of the other college campuses in the most efficient order (recursively choose the campus closest to the previous campus).
d. Display the total distance traveled e. Allow the college student to purchase multiple traditional souvenirs when visiting the college campuses

6. When taking any trip:
a. A college student can purchase multiple traditional souvenirs
b. Your team must keep track of the number of traditional souvenirs purchased at each campus c. Display the total amount spent at each college campus and a grand total for all campuses visited

7. Maintenance (administrator only - requires a password to gain access)
a. Provide the capability to add new college campuses and their corresponding souvenirs by having your program read from an input file given to the class b. Provide the capability to change the prices of the traditional souvenirs c. Provide the capability to add new traditional souvenirs d. Provide the capability to delete traditional souvenirs

8. Provide the capability to visit the 13 college campuses starting at Saddleback.
a. Display the total distance traveled b. Allow the college student to purchase multiple traditional souvenirs when visiting the college campuses



- Coding Standards
  - Namespaces
    - use scope resolution operator (no using namespace std)
  - Variables
    - use descriptive names
  - Functions
    - opening bracket on following line for functions only
    - Bracket examples:

      void func()
      {
      if (boolVal) {
      
  - Classes
    - start with a capital letter
    - follow encapsulation paradigm (keep data members and helper functions private)
    - Misc.
      include guards in header file
      test build and features before pushing to avoid compilation errors or crashes
      verify data from file after implementation
      use descriptive commit messages
      Team Rules
      No bullying alright kids.
      Stay in contact via discord.
      Tell others on discord when you are going to commit.
