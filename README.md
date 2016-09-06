# lab03

## What do you think is the type of each of the following fields? 
* private int count; The field type is integer. The user can only input an integer for this to work.
* private Student representative; The field type is Student.
* private Server host; The field type is Server.

## What are the names of the following fields? 
* private boolean alive; This is named "alive"
* private Person tutor; This is named "tutor"
* private Game game; This is named "game"

## From what you know about the naming conventions for classes, which of the type names in teh above questions would you say are class names?

Student, Server, Person, and Game are class names because they are capitalized.
3
## In the following field declaration from the `TicketMachine` class  
```
private int price;
```
does it matter which order the three words appear in? Edit the TicketMachine class to try different orderings. After each change, close the editor. Does the appearance of the class diagram after each change give you a clue as to whether or not other orderings are possible? Check by pressing the Compile button to see if there is an error message. Make sure that you reinstate the original version after your experiments! 

It does not matter is "private' is there or not.  However, you cannot switch the order of "private" and "int".  "int" must be present to let the program know that the input has to be an integer.

## Is it always necessary to have a semicolon at the end of a field declaration? Once again, experiment via the editor. The rule you will learn here is an important one, so be sure to remember it. 

It is always necessary to have a semicolon at the end of a field declaration.  It acts to imply the end of a sentence or declaration.  Otherwise, it will combine with the next declaration and will not be read correctly.

## Write in full the declaration for a field of type `int` whose name is `status`.

private int status

## To what class does the following constructor belong?
```
public Student(String name)

This belongs to the class Student.
```
## How many parameters does the following constructor have, and what are their types?
```
public Book(String title, double price)

This has two parameters.  The first is of type "String" and the other is of type "double"
```
## Can you guess what types some of the `Book` class’s fields might be, from the parameters in its constructor? Can you assume anything about the names of its fields?

Some of the fields might be the title and author, which would be of string type.  Number of pages would be of int type.  


## Suppose that the class `Pet` has a field called `name` that is of the type `String`. Write an assignment statement in the body of the following constructor so that the `name` field will be initialized with the value of the constructor’s parameter.
```
public Pet(String petsName)
{
name=petsName;
}
```
## The following object creation will result in the constructor of the `Date` class being called. Can you write the constructor’s header?
```
new Date("March", 23, 1861)
```

Try to give meaningful names to the parameters.

private Date(String month, int day, int year)
