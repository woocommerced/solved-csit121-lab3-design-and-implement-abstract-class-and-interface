Download Link: https://assignmentchef.com/product/solved-csit121-lab3-design-and-implement-abstract-class-and-interface
<br>
Following completion of this task, students should be able to:

<ul>

 <li>Design and implement abstract class and interface</li>

</ul>

<strong>Question 1 </strong>

Declare and implement an <strong>abstract</strong> <strong>class</strong> called Ship that has the following:

<ul>

 <li>An attribute to represent the name of the ship.</li>

 <li>An attribute to represent the year that the ship was built.</li>

 <li>A default constructor to initialize the attributes.</li>

 <li>Accessor methods and mutator methods for each of the attribute.</li>

 <li>An <strong>abstract method</strong> called displayDetails().</li>

</ul>

Declare and design a subclass of Ship called CruiseShip. The CruiseShip class should have the following: § An additional attribute to keep the maximum number of passengers.

<ul>

 <li>A default constructor to initialize the attribute in CruiseShip as well as the Ship § Accessor methods and mutator methods for its attribute.</li>

 <li>The displayDetails()method that will display all details from Ship and <sub>CruiseShip</sub>.</li>

</ul>

Declare and implement another subclass of Ship called CargoShip. The CargoShip class should have the following:

<ul>

 <li>An attribute to keep the cargo capacity in tonnage.</li>

 <li>A default constructor to initialize the attribute in <sub>CargoShip</sub> as well as the Ship § Accessor methods and mutator methods for its attribute.</li>

 <li>The displayDetails()method that will display all details from Ship and <sub>CargoShip</sub>.</li>

</ul>

Write a main() method in another class called ShipApp. Declare an ArrayList&lt;Ship&gt; to keep several CruiseShip and CargoShip objects. Use a simple menu to allow the user to

<ul>

 <li>add either a CruiseShip or a CargoShip</li>

 <li>edit either the number of passengers for a CruiseShip or the cargo capacity for the CargoShip</li>

 <li>display all the objects in the ArrayList.</li>

</ul>


