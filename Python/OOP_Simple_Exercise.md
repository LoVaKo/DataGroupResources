# Python OOP Exercies
This is a simple exercise for you to get to know OOP in python. 

Create a program, using OOP concepts, using the following steps:

## Step 1: Create the `Animal` Class
- Create a class `Animal`
- Create a constructor method
- Attributes should be: `name` and `favorite_food`
- Create an instance of `Animal` to experiment with and see if everything works correctly

## Step 2: Create behaviour for the `Animal` Class
### Method `make_sound`
- Create a method `make_sound`
- Have this method print out a sentence like: `<name> says: BRRAIHOIODG`

### Method `eat`
- Create a method `eat`
- have `food` as a parameter
- there are two possible outputs for this methods. If the food argument passed to this method is the same as the animals favorite food, the print statement is much more enthusiastic than if it is not the animals favorite food!
  - `<name> is devouring his favorite food: <food>`
  - `<name> is eating <food>`
 
## Step 3: Some inheritance and polymorphism
But what is an animal? Isn't that a bit abstract? Lets create some CHILD classes.
- Create the class `Cat` that *inherits* from the Class Animal.
- Override the method `make_sound` to have it make a cat's sound.
- Do the same for the class `Dog`

### BONUS
In real life, the animal would either be a Cat or Dog. It could not be just an 'Animal' without being more specific. The concept of animal is abstract. For this, we have abstract base classes (ABC). These classes define shared behaviour that can be inherited by other classes. Read up on the subject and change class `Animal` into an abstract class.

## Step 4: Experiment
Try to figure out if everything works as expected. If you'd like, you could create more attributes and behaviour, more animals, have them interact etc.
