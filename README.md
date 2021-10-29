## Input
There are many different ways to get user input. We are going to use the `Scanner` class. In order to use the class to get input, we must...

1. `import java.util.Scanner;`
2. Create a Scanner output
3. Output prompt to guide user

`Scanner user = new Scanner(System.in);`

## Input types 
1. `nextInt()` reads integer value from user
2. `nextFloat()` or `nextDouble()` reads a decimal value from user
3. `nextBoolean` reads boolean value from user
4. `nextLine()` reads a String value

## String
A collection of characters. Strings are immutable, which means they cannot be changed.

Ex: `"My name is Mr. Nick."`

Ex: `"I have four dogs."`

### Contructing String Objects

We can create string objects similar to primitive data types.

`String Name = "Nick";`

### Conctentation of Strings

Example:

`String firstName = "Matt";`

`String lastName = "Jones";`

`String fullName = firstname + lastname;`

Example: 

`String id - 5;`

### Comparing Strings

In Java, you can compare strings using two different methods.
- `equals()` method
- `compareTo()` method

**For the equals() method:**

`string1.equals(string2));`, this returns a boolean value, either true if the two strings are equal, or false otherwise.

Example:

`String dog = "Dog";`

`String cat = "Cat";`

`System.out.println(dog.equals(cat));` results in false

**For the compareTo() method:**

`string1(compareTo(string2));`

This method returns:
- Returns 0 if the two strings are equal
- Returns a value less than 0 if the first string precedes the second string in the dictionary
- Returns a value greater than zero if the second string precedes the first string in the dictionary
(difference in ASCII value of the characters being compared)

### Indexing String

Even though strings are inmutable, you are able to take parts of a string to use for a new string.

**Method: substring()**

The substring() method has two different forms:
- string1.substring(5)
- The first for takes a single integer input and returns the characters of the string from the index of the input to the end.

Example:

`String dinosaur = "Triceratops";`

`String half = dinosaur.substring(5);`



- `string1.substring(Integer num1, Integer num2);`
- The second form takes two integer inputs and returns the characters of the string from the index of the first input to the character before the index of the second input.

Example:

`String dinosaur = "Triceratops";`

`String part = dinosaur.substring(2,6);`

### Other String Methods ###

There are other string methods that are useful for you!!

`String name = "Nicholas";`

`int length = name.length();` 









