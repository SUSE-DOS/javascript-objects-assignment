[<img src="assets/images/su-logo.png" alt="Skills Union Logo" height="80px" />](https://www.skillsunion.com/)

# JavaScript Objects: Assignment

## Problems

### 1: The Reading List

Let's write a small program to keep track of which books you read and which books you want to read.

1. Create an **Array** of **Objects**
1. Each **Object** in the **Array** should describe a book and have the following properties:
   1. Title (**String**)
   1. Author (**String**)
   1. alreadyRead (**Boolean**)

      A **Boolean** that indicates whether you already read the book
1. Iterate a.k.a Loop through the **Array** of **Objects** containing the books
1. For each book, print the book title and author as shown below:
   ```
   The Hobbit by J.R.R. Tolkien
   ```
1. Now use the `if/else` statement to change the output depending on whether you have already read the book or not
   1. If you have read the book, print a string as shown below:
      ```
      You have already read "The Hobbit" by J.R.R. Tolkien
      ```
   1. If you haven't read the book, print a string as shown below:
      ```
      You still need to read "The Lord of the Rings" by J.R.R. Tolkien
      ```

```js
// Your Answer
```

### 2: The Fastest Ship in the Galaxy

Let's start you with a small ship to work on. Follow each prompt in the comments below to solve the given problem and add your solution code next to it.

```js
const ship = {
   name: 'Millennium Falcon',
   speed: 42,
   crew: ['Han Solo', 'Chewbacca'],
   passengers: [],
   famous: true,
   heardOfIt: function() {
      console.log("You've never heard of the millennium falcon?");
   }
};

// Console Log the Ship Name

// Your Answer


// Change the Speed to 9999

// Your Answer


// Add 2 passengers, "Leia" and "Luke"

// Your Answer


// Console Log whether it's famous or not

// Your Answer


// Ask if you've heard of the millenium falcon

// Your Answer


// Remove Leia from the crew

// Your Answer


// Add a new property called "color" and set it equal to "beige"

// Your Answer


// Add a new property called "missions" and set it equal to an empty object

// Your Answer


/*
   Add the following 3 properties to the "missions" property object

   1. kashyyk: true
   2. escapeFromAsteroid: "fun"
   3. smuggledCargo: ["Prisoners", "Stolen Goods", "Spice"]
*/

// Your Answer


// Bonus Problem
// You are going to need to use a search engine for this

// Delete the "famous" property

// Your Answer
```

## Submission Guidelines

- Cite any relevant sources consulted during your research
- Solve the problems using your own code
- Do not copy and paste solutions from the source material
