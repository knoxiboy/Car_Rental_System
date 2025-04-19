<h1>Car Rental System</h1>

A Java-based Car Rental System that simulates the core functionality of a real-world rental service. 
This project is built using all major Object-Oriented Programming (OOP) concepts such as Encapsulation, Inheritance, Polymorphism, and Abstraction.

<h3>Features</h3>

*Add cars to the rental system <br>
*Register and manage customers <br>
*Rent a car to a customer for a specified number of days <br>
*Return rented cars <br>
*Calculate and display rental price based on days rented <br>
*Simple menu-driven console interface <br>


<h3>OOP Concepts Used</h3>

Encapsulation: Private fields with public getters/setters for data hiding

Inheritance: Common properties inherited by specialized classes (e.g., Vehicle -> Car)

Polymorphism: Method overriding and dynamic method dispatch used for rental calculation

Abstraction: Interfaces and abstract classes to define core functionalities


<h3>Demo</h3>

<h4>Sample Flow:</h4>
1. Admin adds available cars <br>
2. Customer registers and selects a car <br>
3. System checks availability and books the car <br>
4. Bill is generated based on rental duration <br>
5. On return, system updates the availability <br>


<h4>Welcome to Car Rental System</h4>
1. Add Car <br>
2. Register Customer <br>
3. Rent a Car <br>
4. Return a Car <br>
5. View Inventory <br>
6. Exit <br>


<h3>Installation</h3>
1. Clone the repository: <br>
git clone  https://github.com/knoxiboy/Car_Rental_System.git
cd Car_Rental_System 
<br>
<br>
2. Compile the code: <br>
javac Car_Rental.java
<br>
<br>
3. Run the program: <br>
java Car_Rental
<br>

<h3>Project Structure</h3>
<pre> 
| Class Name        | Description                                                                 |
|-------------------|-----------------------------------------------------------------------------|
| Car               | Represents a car with ID, brand, model, base price per day, and availability|
| Customer          | Represents a customer with ID and name                                      |
| Rental            | Represents a rental transaction (car, customer, days)                       |
| CarRentalSystem   | Manages cars, customers, rentals, and provides main system functionality    |
| Car_Rental        | Contains the main method to run the application                             |
</pre>


<h3>Technologies Used</h3>
*Java (OOP, File I/O, Collections) <br>
*CLI-based UI (simple terminal interaction)


<h3>Requirements</h3>
*Java 8 or higher <br>
*Command-line interface (CLI)


<h3>Future Enhancements</h3>
*Add GUI using JavaFX or Swing <br>
*Store data in a database <br>
*Payment and billing system <br>
*Admin/customer login system <br>


<h3>Contributing</h3>
Contributions are welcome! If you'd like to improve the system, feel free to fork the repo, open an issue, or submit a pull request.
