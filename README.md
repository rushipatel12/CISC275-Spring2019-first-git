# CISC275-Fall2018-first-git
1. Create java files to make this code compile and run. 

Classes are in lab3class.java file

2. What five objects are created in the main?

The five objects created in main are an List<Dog> object, 3 Dog objects (Dog("Fido",4),Dog("Fido",3),Dog("Alfie",4)), and a Comparator<Animal> object.

3. Can you spot the comparator constructor call? Where is the class definition for the comparator?

The comparator constructor call is Collections.sort(dogs, new Comparator<Animal>(). 

The class definition for the comparator is within the constructor where the method is overridden is inside of the collections sort method. Collections.sort(dogs, new Comparator<Animal>(){}. The new Comparator<Animal>() line is the class definition for comparator. 
