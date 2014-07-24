# Methods, Interfaces and Embedding - Exercises

## Embedding

### Exercise 1
Declare a struct type named Animal with two fields associated with all animals. Declare a struct type named Dog with two field associated with a dog. Embed the Animal type into the Dog type. Declare and initalize a value of type Dog. Display the value of the variable.

### Exercise 2
From exercise 1, add a method to the Animal type using a pointer reciever named Yelp which displays the literal string "Not Implemented". Call the method from the value of type Dog.

### Exercise 3
From exercise 2, add an interface named Speaker with a single method called Yelp. Declare a value of type Speaker and assign the address of the value of type Dog. Call the method Yelp.

### Exercise 4
From exercise 3, implement the Speaker interface for the Dog type. Call the method Yelp again from the value of type Speaker.