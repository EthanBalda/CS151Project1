# CS151Project1
/*
The purpose of this project is to generate thirty random whole numbers between 1 and 10, insert them into a vector in descending order, then and print the numbers in ascending order:

Use the following plan of attack:

Open a new C++ project or repl, then a new C++ program,
In the program file, create a  main  function.
In  main,  create an empty vector of  int  elements.
Use the  srand  function to change the "seed" for generating random numbers so that the  rand  function will generate different random numbers every time your program is run.
Use the  rand  function to generate a random number whole number between 0 and  RAND_MAX  (if you are using repl.it, the value of  RAND_MAX  is 2,147,483,647, and if using Dev-C++,  RAND_MAX  is 32,767).
Convert this number into a number between 1 and 10.
hint: use the  %  operator.
Use a loop to scan the vector until you find the position of an element containing a number that is less than the random number just generated above or until you reach the end of the vector.
Use an iterator to insert the random number into the vector at that position (or at the end of the vector).
Go back to step 3 and perform again until the vector contains 30 random numbers
After all 30 numbers have been generated and inserted into the vector, they should appear in descending order in the vector.
Use the  back  and  pop_back  functions in a loop to print the numbers in ascending order on the console.  Use a  while  loop until the vector is empty.
*/
