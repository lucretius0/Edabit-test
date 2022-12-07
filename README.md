# A few problems from Edabit, uploaded as a test of git/github


1 Multiple choice tests: 
```
Your task is to write a program which allows teachers to create a multiple choice test in a class called Testpaper and to be also able to assign a minimum pass mark. The testpaper's subject should also be included. The attributes are in the following order:

subject
markscheme
pass_mark

As well as that, we need to create student objects to take the test itself! Create another class called Student and do the following:

Create an attribute called tests_taken and set the default as 'No tests taken'.
Make a method called take_test(), which takes in the testpaper object they are completing and the student's answers. Compare what they wrote to the mark scheme, and append to the/create a dictionary assigned to tests_taken in the way as shown in the point below.
Each key in the dictionary should be the testpaper subject and each value should be a string in the format seen in the examples below (whether or not the student has failed, and their percentage in brackets).
```


2 Freshly Made Pizzas

```
Create a Pizza class with the attributes order_number and ingredients (which is given as a list). Only the ingredients will be given as input.

You should also make it so that its possible to choose a ready made pizza flavour rather than typing out the ingredients manually! As well as creating this Pizza class, hard-code the following pizza flavours.

Name	Ingredients
hawaiian	ham, pineapple
meat_festival	beef, meatball, bacon
garden_feast	spinach, olives, mushroom
```

3 To the Right, to the Right! 

```
Create a class that imitates a select screen. For simplicity, the cursor can only move right!

In the display method, return a string representation of the list, but with square brackets around the currently selected element. Also, create the method to_the_right, which moves the cursor one element to the right.

The cursor should start at index 0.
```