Download Link: https://assignmentchef.com/product/solved-csci251-assignment2-inheritance-and-polymorphism
<br>
This assignment aims to provide you with some experience in writing codes using C++ programming language that covers the following topics:

<ul>

 <li>Inheritance and Polymorphism</li>

 <li>Overloaded operators and friends</li>

</ul>

<table width="733">

 <tbody>

  <tr>

   <td width="733"><strong> </strong><strong>Remember that: </strong><strong>1.         </strong><strong>All programs should be able to run on the lab’s computers. </strong><strong>2.         </strong><strong>You must put the following information on the header of each text and source file you will be submitting in this assignment:  </strong><strong>     Student’s full name:   </strong><strong>     Student’s ID:   </strong><strong>     Modification Date:  </strong><strong>     Purpose of this file (or program):   </strong><strong>3.         </strong><strong>Assignments that are not able to be compiled will result in zero mark given to the assignment. </strong><strong>4.         </strong><strong>You must only use the C++ features that have already been covered in the lectures </strong><strong> </strong></td>

  </tr>

 </tbody>

</table>

<strong>Question: </strong>

For this assignment, you are required to write C++ codes to represent a simple application for a fantasy roleplaying game. In this game, you have four different type of creatures: wizard, elf, dwarf, and demon. Each creature has attributes to represent its name, strength and hit points. The strength is used to measure how much damage this creature can inflict on others while the hit points is to represent how much damage this creature can sustain.

In a particular game, when a creature attacks, we can request to get the damage value the creature can inflict. Your program should decide on the general strength and hit point value when a creature is created and this will be the initial value for all creatures.

The damage value is determined by its strength. However, the damage can be more depending on the type of the creature. Demons can inflict 50 additional damage with a 5% chance. Dwarf inflict double damage with a 10% chance while Elf are fast enough that they get to attack twice. Wizard can inflict magical damage that causes their opponent to miss their next attack with either 50% chance if no wand is used or 90% chance when a wand is being used.

Every time a creature is attacked, the hit points are reduced based on the damage caused by the creature attacking it. If the hit points reaches 0 or less, the creature is pronounced dead and the object representing the creature should be destroyed. There can be more than one type of creature in a game played.

Your application should allow several games played one after another. In each game, the user may select any two creatures to be created and and fight. The winner may stand a chance to fight another chosen opponent or the user may choose to quit the game.

The following are the requirements that must be implemented in the application

<ul>

 <li>Design and implement classes using inheritance to represent the creatures. The base class should be made abstract. Identify the suitable attributes for each classes. All derived classes must have unique attributes apart from the attributes inherited from the base class. Identify and implement suitable constructors, accessors, mutators, and also abstract method(s).</li>

 <li>You must also include suitable overloaded operators to your classes. At least three different overloaded operators should be used.</li>

 <li>There must be at least one friend function declared.</li>

 <li>Polymorphism must be implemented. To do this, all the creatures created must be stored in a single array. There must be demonstration on the use of polymorphic call and also dynamic cast in your application.</li>

</ul>

You are free to demonstrate how the game can be played. However, the following should be present in some ways:

<ul>

 <li>Status of each creature (or at least the creatures involved in the current fight)</li>

 <li>The attacking creature and the creature being attacked</li>

 <li>The damage value when an attack is made</li>

 <li>The winning creature</li>

 <li>The creature that is destroyed</li>

</ul>