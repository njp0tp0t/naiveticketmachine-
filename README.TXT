Project: naive-ticket-machine
Authors: David Barnes and Michael Kölling

This project is part of the material for the book

   Objects First with Java - A Practical Introduction using BlueJ
   Seventh edition
   David J. Barnes and Michael Kölling
   Pearson Education

It is discussed in chapter 2.

Purpose of project: To illustrate the basics of fields, constructors, and methods.
How to start this project: Create one or more TicketMachine objects.


1. getPrice= 5
   insertMoney= 25
   getBalance= 25
inserted exact amount required for a ticket (5). New balance: 25+5= 30
printTicket method: ##################
                    # The BlueJ Line
                    # Ticket
                    ##################
                    
2.  After printing a ticket, the machine's balance set back to 0

3. 1- Inserted 100 and printed a ticket, balance is set back to 0.
      No refund received.
   2- Inserted 4 and printed a ticket (cost of a ticket is 5).
      the ticket was still printed even when insterting less than it's required.

4. 1- A ticket machine should give a refund if too much is given.
      Ex: inserted money: 100  Ticket price: 5  Amount to be given back: 9      
   2- A ticket machine should identify if an amount given is enough to issue a ticket.

5. Created another ticket machine for a tickets of a different price.
   only difference: price is different (10)

7. When changed to "class public", everything else under it becomes white
   a bunch of errors are shown like "<identifier> expected", "class, interface, enu, or record expected",
   and "unnamed classes are a preview feature and are disabled by default".
   When trying to compile, there are 8 errors found in class.
   It is required to type "public class" instead of "class public" in order to avoid errors.
   
8. Yes, it is possible to leave out the word "public". There are no errors.

9. No, it is not possible to leave out the word "class". Everything turns white and a bunch of errors are shown.

11. 1- No return type (int,void,String,etc)
    2- Same name as the class
    
12. 1- type: int
    2- type: Student
    3- Server
    
13. 1- name: alive
    2- name: tutor
    3- name: game
    
14. Person, Game, Server and Student.

15. - private price int= error
    - price private int= error
    - price int private= error
    - int private price= error
    - int price private= error
conclusion: yes it matters, it should always be in order of "private int price"

16. It is required to add a semi colon at the end of a field declaration, because in Java a semi colon indicates the end of a statement
and without it Java wouldn't know where the declaration stops.

17. private int status

18. public Student(String name)
    belongs to class Student
    
19. public Book(String title, double price)
    number of parameters: 2  types: String and double
    
20. Do you think the values of the constructor’s parameters will need to be stored somewhere persistent?
    : Yes
    Can you guess what types some of the Book class’s fields might be, from the parameters in its constructor?
    : Yes
    Can we know anything for sure about the names of its fields? 
    : Yes
    
21. public Pet(String petsName)
    {   
        name = petsName;
    }
    
22. public Date(int day, int month, int year)

23. 1- Method names are different.
    2- Return satements are different.
    
24. What is the new balance?

25. The name of an accessor method can be different than the name of the field associated with.

26. Done

27. It says "missing return statement"

28. getPrice is type "int" and printTicket is type "void".

29. No they do not have return statements, because type "void" can't return any value.

30. getBalance = 0
    inserted 2
    new balance = 2

31. /**
    * Increase score by the given number of points.
    */
    public void increaseScore(int points)
    {
        score = score + points;
          // TODO: Increase score by the value in points.
    }
    
32. Yes, the addCredits method is a mutuator because it modifies the state of the object Student.
    credits before adding: 0
    credits after adding 67 credits: 67
    
33. /**
    * Reduce price by the given amount.
    */

    public void discount(int amount)
    {
        price = price - amount;
        // TODO: Subtract amount from price.
    }
    
34. public void setAge(int currentAge)
    {
        age = currentAge;
    }
    
35. 