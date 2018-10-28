# X-Team 14 Project Proposal - Bucky's Ballhouse Inventory Management

See https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet#code for tips on using *Markdown* tags to format __.md__ files

## Goal

Work as a team to create a project proposal for your X-team to complete together.
The project does not have to be extremely difficult,
but there must be work to do for each member of your team.
Be sure to submit corresponding image files, i.e. figure1.png (or figure1.jpg) for each figure.

## Grading: To earn full credit, your team's proposal must include:

* (md) documentation: [this file] describing purpose and use of your program

* Description of a program that has:

  ** a main Java program class in a file named Main.java
  
  ** a custom data structure designed and built by your team
  
  ** comprehensive testing of individual units
  
 Caution: You are not being asked to implement this program, at least not yet. 
 We just want your group to make a proposal or pitch for your program.
 
 Tip: Your custom data structure can be composed of or extensions of data structures that you have learned and used in previous programming assignments.  We're looking for decisions about how to build a high-level data structure that will likely have lower-level components.

## Problem Description

Briefly describe a problem that your team would like to solve.  
Describe at a high level a program that could solve that problem.

Our team would like to solve an inventory management problem for a small local sports retailer, "Bucky's Ballhouse".
Our program will store the inventory of the store's goods and manage outgoing sales and incoming orders. Our user interface
will allow employees to add products to the inventory when shipments arrive, and allow them to remove them after sale of
products. Our program will have the functionality to generate inventory reports and and it is possible that it will be
able to schedule orders when product quantities get to certain levels.

## Questions to answer for Exercise #2

1. Name: Give your project proposal a name (and edit the top line of this file)

Bucky's Ballhouse Inventory Management

2. Output: Describe the output your program will produce.  Include and example format of the output produced.

Our output will be a report of current inventory levels to make management aware of products they may need to 
order more or less of. Management or employees will be able to set minimum levels of product quantities 
and when products drop below that level, products will be added to an order form. Once the order form is created, it
can be outputted to the employee to be reviewed.

3. Input: Describe the data that is needed to solve your problem. Include an example format of the input data.

The data needed to solve the problem will be product quantities currently on hand, and desired quantity of products.
Employees will be able to input quanitity of a product to order and add it to the next order form, and they can
also input quanitites when shipments arrive. When products are sold they will be removed from the inventory.

4. User Interface: Describe a user interface for your program.  Use text menus or a simple graphic user interface.

Currently, we plan on developing a simple GUI that will have buttons, input boxes, and drop down menus that will allow 
the user to interact with the Inventory Management program. The buttons will be for adding inventory when shipments arrive
and adding a sale to the system (that removes inventory). Buttons for generating inventory reports and viewing order forms
will also be available. See figure1:
![Image of user interface](https://github.com/JunhengWang/cs400-X-Team-14/blob/master/figure1.png)

5. Types List: Break your solution idea down into units that you think can be implemented with a single class.
Name each interface or class and briefly describe its function or purpose.

Inventory Class (Data Structure): hash table or list to store onjects of type product
Product Class (Nodes): nodes of product type that will be stored in the data structure. There may be
classes that inherit this class (ex. Equipment, apparel, etc)
Main Class (runs program): Main class will have main method for running Inventory Management Program




## Edit and Submit this file and any figures referenced by this document.

