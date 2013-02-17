Java
====

CS102 Homework Assignment 4


Computer Science II
CS102-Ames Fall 2013
HW4—Linked Lists
10 points
Assignment: Create a linked list class that contains String’s, and has the methods listed 
below.  Test your class with the NameList.java file available on BBV().
Due: Friday 2/8, 5PM
Turn In: Submit a copy of your Java sources to BBV.  
Use the generic LinearNode.java class from the text and recent demo’s; you can find it in 
the HW4 area of BBV.  Don’t alter this file, unless you check with me first.
Also on BBV is a starting point (“NameList.java”) for making a linked list of LinearNode’s 
that contains Strings.  And, I’ve provided a HW4Tester class with a main() that you can use 
for testing purposes.  Don’t make any changes to the tester itself unless you check with me 
first.  But, you have plenty of methods to write inside of NameList.
Your finished NameList class should have the following features:
 A head variable for keeping track of the list.
 A default constructor for initializing head so that the list is initially empty.
 An add method that adds a String to the list**.
 A delete method that removes a particular string from the list.  If the string to be 
deleted is not in the list, no action should be taken.  If the string exists more than once 
in the list, only one of them should be removed.
 A size method, that returns the number of elements in the list.
 A toString method that returns a string containing all names in the list, in order, with a 
newline character (“\n”) after each name.
** And now for the twist:  the linked list must be maintained in alphabetical order.  The add
method must not simply add the string to the beginning or end of the list, but must look through 
the list to find the proper insertion point.
See the java library documentation for the method compareTo in the String class to see 
how to tell if one string comes before/after another alphabetically.
One last item: make use of generics, as defined by the LinearNode.java file.  There should be 
no warnings in either of the .java files.
Check your results: see that the names deleted near the bottom of the main really are gone, 
and that the correct number of names is present, and that both printed lists (before, after 
deletions) are in alphabetical order./**
* Linked List Homework, #4
* PUT YOUR NAME HERE
* Spring 2013
*/
Download this file (NameList.java) from BBV
public class NameList
{
    // declare your head variable here
public NameList() {
        // You write this constructor (if needed)
    }
public void add(String name) {
        // You write this
    }
public void delete(String name) {
        // You write this
    }
public int size() {
        // You write this
    }
public String toString() {
        // You write this
    }
}
