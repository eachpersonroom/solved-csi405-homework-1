Download Link: https://assignmentchef.com/product/solved-csi405-homework-1
<br>
Problem 1: Create an Employee class

Create a class to represent Employee information called <em>Employee.</em> This class includes three pieces of information as instance variables—a first name (type String), a last name (type String) and a monthly salary (type double). Your class should have a constructor that initializes the three instance variables. Provide a set and a get method for each instance variable. If the monthly salary is not positive, set it to 0.0. Write a driver class named <em>EmployeeTest</em> that demonstrates class <em>Employee’s</em> capabilities. Create two <em>Employee</em> objects and display the yearly salary for each Employee. Then give each Employee a 10% raise and display each Employee’s yearly salary again.

Problem 2: Methods

Create a class called <em>HW1Problem2</em>. Create the following (public) methods in the class:

<ol>

 <li>Write a method called <em>multiple</em> that takes two integers as its arguments and returns true if the first integer is divisible evenly by the second one (i.e., there is no remainder after division); otherwise, the method should return false.</li>

 <li>Write a method called <em>reminder </em>that takes an integer as an argument and returns the remainder of that value divided by 7.</li>

 <li>Write method <em>distance</em> to calculate the distance between two points (x1, y1) and (x2, y2). All numbers and return values should be of type double.</li>

 <li><strong><u>BONUS:</u></strong> Write a method that uses random numbers to simulate 10 flips of a coin.</li>

</ol>

Incorporate all of the above methods in a driver class <em>Problem2Driver</em>. Allow user to provide inputs for the arguments of the methods and also display results from the methods.

Problem 3: Bank simulation Model the classes below:

<ol>

 <li>CheckingBankAccount – A checking bank account has value, a person can withdraw, deposit money to the account</li>

 <li>Address – This is a simple class which has all String fields to represent an address (ex. Address line 1, line2, City, State, Zip)</li>

 <li>Person – A person has a first and last name, address and has a CheckingBankAccount</li>

 <li>Bank – Bank is “associated” with the checking account. Bank has a String name and address. You do not need to have a CheckingBankAccount object within this class. However it is upto you to design/model this representation.</li>

</ol>

For simplicity we will assume there is only one instance of each classes described above. Ex. Bank only has 1 account, an account is only linked to 1 person and a person only has single address.

The “has-a” relationship here shows aggregation. Example a person “has-an” address – meaning you can use the Address class within the person class to represent the address for a person.

Once you have the above classes create a main method in the Bank class. Simulate a person arriving to the bank (print the person’s name, and the bank’s name), then simulate the person opening an account with initial deposit of $1000. Simulate a deposit of $1000 and a withdrawal of $500. Every time a withdrawal or deposit happens, a receipt is printed with the name, address of the person and his/her current balance.

Create the UML diagrams of all the classes in <strong>all</strong> of your projects. The UML diagrams should follow the <strong><u>exact</u></strong> formatting shown in class slides