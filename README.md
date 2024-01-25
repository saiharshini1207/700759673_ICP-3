#Description for the employees program

1. This python code defines two classes "employee" and "fulltimeemployee".
2. "EMPLOYEE CLASS" defines the data member "no_of_employees" to count the number of employees.
3. And we initialize a constructor with the paramates "name", "familyname", "salary", "department".
4. And next we defines a "average salary method" to calculate the average salary of the list employees.
5. It calculates the average salary by taking the employees as a parameter.

6. For "FULLTIMEEMPLOYEE" class is a subclass of the class "employee" that lists the full time employees.
7. And for the constructor it calls the constructor of the parent class (Employee) using super().__init__ and inherits the attributes and behavior of the Employee class.
8. "full_time_benefits" method it prints a message there are few benefits as a full time employee.
9. "MAIN" function demonstrates the usage of the both classes.
10. In the we creates an empty list employees[] to store all the employees.
11. Create instances of FulltimeEmployee and Employee.
12. Call the f"ull_time_benefits" method for "FulltimeEmployee" instances.
13. We Calculate and prints the average salary of all employees using the "average_salary" method.
14.And we append some employees by giving the values based on the paramaters that we intialized in a constructors.
15. And the "main" block ensures the main function when program is run.
  


#Description for the numpy program

1. In this program first we import the numpy
2. Next we gonna construct a constructor by passing some parameters.
3. And we define the function "replace_maxmion" that takes a NumPy array, a replacement value, and an axis as input parameters and replaces the maximum value in each row of the array with the specified replacement value along the specified axis.
4. And now we initializes the main function by creating a random vector of size 20 as a floating numbers.
5. Now replacing the array shape from 4 to 5 and then by using "replace_maximum" we replace maximum value in each row with 0 along with axis 1.
6. Finally for the output original random vector, reshaped array, and the modified array are printed.
