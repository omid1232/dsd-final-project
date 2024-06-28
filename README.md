# verilog parking implementation
this is an implementation of a parking for university with extra free space with verilog
the space of 700 is divided between two groups which are university members and free users.
the space for university members decreseases from 13:00 to 16:00 and for other hours it stays the same.
at the start of the day which is 8:00 university has 500 space until 13:00 which then begins to decrease with the rate of 50 per hour
and then stops at 16:00 which means it will have 300 space.
#tools
verilog
#implementation
to implement the parking I used signals to show if a car entered or exited and whether if it was a university member or a free user
also I used clock and reset signals to start the program for the beginning and clock the simulate time and calculate hour based off it
the outputs consisted of signals and integers to show if there is room in the parking for either free or university space and the number of cars 
in the parking for each section.
#test
I wrote multiple testbenches to simulate different scenarios. here is one of the tests and the output of that test
![image](https://github.com/omid1232/dsd-final-project/assets/119661267/186acef7-b7ea-4ef7-bc39-0c5d29f027f5)
![image](https://github.com/omid1232/dsd-final-project/assets/119661267/14d52ae0-d19e-4def-9777-408c0f7e5844)
and it's output:
![image](https://github.com/omid1232/dsd-final-project/assets/119661267/577e80f1-12d4-4dae-a5a6-57f48308003b)
other testbenches with their outputs are in the zip file with in-depth explanation
