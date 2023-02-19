# ListView Lab

## Objective: 
In this lab, you will learn how to implement ListView in your Android Studio apps and understanding how the Adapter works!  

By the end of this lab, you will continue from the previous labs and you will be adding a User ListView to your app.  

## Instructions:

In this lab, we'll be making well designed pages with the possibilty to move between activities and implementing option menus!  

1. User class:
  - Open a Java file for your User class.
  - Add the following attributes to your class:
    - Name.
    - Email.
    - Password.
    - you can add any **additional attributes** you want.
  - Using generate, add a constructor, setters, getters and a toString.

2. ListView in XML:
  - Add a `ListView` component to your activity layout file.
  - Open an XML file for the **custom row** in the layout folder and design it, should at least include:
    - Name.
    - Email

3. Creating an ArrayAdapter: 
  - Create a new class named `UserArrayAdapter`.
  - Copy the [ClassNameArrayAdapter](https://docs.google.com/document/d/148VUAErpZurx5NGTrQZ2Vxm_GZXy7Mt39oZ5b2plvAo/edit) template.
  Make sure to write your class name instead of the spots where it says ClassName
  Get the user object from the ArrayList and adapt the objects to the custom row.
  Make sure that the object is not null.
  Get the Views from the custom_row and set the values according to the user objects.

Activity:
Create a user ArrayList and add objects to the list.
Initialize the ListView and find it through its id.
Initialize the ArrayAdapter and create an adapter object.
Set the ListView adapter to the one you made.


##### Call an Instructor/TA to check your completed tasks

### Bonus:

1. When you go to `HomeActivity`, send the email of the user as a **variable** and **display** it in `HomeActivity`.
 
###### make sure you commit and push your code.
