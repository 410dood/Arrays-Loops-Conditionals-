# HW---Arrays-Loops-Conditionals-

Arrays Loops Conditionals
Title: Arrays, Loops, and Conditional Reps 
Type: Homework
Duration: "4:00"
Creator: Alex White
Modified by: Daniel Scott
Course: WDIplus-ATX
Competencies: Arrays, Loops, Conditionals 
Prerequisites: JavaScript 

Homework
Setup
In your terminal, navigate to to the Week_One folder and create another folder called (Wednesday).

Create a javascript file inside your Wednesday folder to record your answers (maybe name it answers.js).

Keep your answers organized! Included a commented header for each section in your answers file.

TEST YOUR WORK! Make sure that your code works 🐘 node name_of_your_file.js.

If you're stuck on something for "too long" or get overly frustrated, make a comment and move on. Return to it later.

After each section (even if you're not fully done with it), add and commit your work.

Please use the commit messages that you see at the end of each section (modify it if you need to). We will see these messages on Github. It will help us to see your progress. If you go back and fix a section, commit again with an updated message.

When you are done with your homework, push it to your origin (this is your Github) and make an issue on our repo.
Final note: You are not alone! Everyone else in the class is working on this as well. Send Slack messages, make a Zoom channel, or meet with the TA to discuss sticking points.

Image of baby doing workout

Easy Going
Write a for loop that will log the numbers 1 through 20.
🔴 The commit message should read: 
"Commit 1 -Easy Going answered"
Get Even
Write a for loop that will log only the even numbers in 0 through 200.
Hint: Think about the increment expression.

🔴 The commit message should read: 
"Commit 2 - Get Even answered"
Excited Kitten
Write code that logs "Love me, pet me! HSSSSSS!" 20 times.

For every even number in your loop, log "...human...why you taking pictures of me?...", "...the catnip made me do it...", or "...why does the red dot always get away..." at random.

Hint: You will need to use Math.random()

Image of cat with funny quote about dot

🔴 The commit message should read: 
"Commit 3 - Excited Kittens answered"
Fizz Buzz
Write a javascript application that logs all numbers from 1 - 100.

If a number is divisible by 3 log "Fizz" instead of the number.

If a number is divisible by 5 log "Buzz" instead of the number.

If a number is divisible by 3 and 5 log "FizzBuzz" instead of the number.

🔴 The commit message should read: 
"Commit 4 - Fizz Buzz answered"
Getting to Know You
Use the following arrays to answer the questions below (name, age, hometown):

const thom = ["Thom", 1000, "Christchurch"]
const karolin = ["Karolin", 16, "New York"]
const kristyn = ["Kristyn", 5, "Pittsburgh"]
const matt = ["Matt H", 186, "Philadelphia"]
Matt H. decides that Thom. can't be named "Thom" anymore. Remove "Thom" from the thom array and replace it with "Gameboy".

Karolin just had her birthday; change Karolin's array to reflect her being a year older.

Change Matt H's hometown from Philadelphia to "Gotham City".

Remove "Pittsburgh" from Kristyn's array and add "Brooklyn".

🔴 The commit message should read: 
"Commit 5 - Getting to Know You answered"
Yell at the Ninja Turtles
Create an array with the members of the ninja turtles (Donatello, Leonardo, Raphael, Michaelangelo)

Use a for loop to call toUpperCase() on each of them and print out the result.

🔴 The commit message should read: 
"Commit 6 - Yell at the Ninja Turtles answered"
Return of the Closets
Below, we've given you examples of Kristyn and Thom's closets modeled as data in JavaScript. Use this data to answer the following questions.

const kristynsCloset = [
  "left shoe",
  "cowboy boots",
  "right sock",
  "GA hoodie",
  "green pants",
  "yellow knit hat",
  "marshmallow peeps"
];

// Thom's closet is more complicated. Check out this nested data structure!!
const thomsCloset = [
  [
    // These are Thom's shirts
    "grey button-up",
    "dark grey button-up",
    "light blue button-up",
    "blue button-up",
  ],[
    // These are Thom's pants
    "grey jeans",
    "jeans",
    "PJs"
  ],[
    // Thom's accessories
    "wool mittens",
    "wool scarf",
    "raybans"
  ]
];
Alien Attire
Kristyn's left shoe has traveled through time and space and turned up in Thom's accessories drawer! Remove Kristyn's shoe from the array and save it to the variable kristynsShoe. Use that variable to add Kristyn's lost shoe to Thom's accessories array.
Dress Us Up
Modify your code to put together 3 separate outfits for Kristyn and Thom. Put the output in a sentence to tell us what we'll be wearing. Mix and match!
🔴 The commit message should read: 
"Commit 7 - Kristyn and Thom have their outfits ready for class - array practice"
Dirty Laundry
Continue looking at the closet arrays:

Time to do laundry - loop through Kristyn's closet and log the sentence "WHIRR: Now washing (item)" for each item in the array.
Inventory
Thom wants to do inventory on his closet. Using bracket notation, log the arrays containing all of Thom's shirts, pants, and accessories.
🔴 The commit message should read: 
"Commit 8 - I loops through their closets".
Multiples of 3 and 5
Yes, you might have tackled this earlier, but try it again (don't look back at your other code 👀)

If we list all the natural numbers below 10 that are multiples of 3 or 5, we get 3, 5, 6 and 9. The sum of these multiples is 23.

Find the sum of all the multiples of 3 or 5 below 1000.

👏 You just solved Project Euler problem 1! 👏

🔴 The commit message should read: 
"Commit 9 - Project Euler Problem 1 answered"
HTML & CSS
Watch the following videos as a refresher on HTML and CSS. We recommend that you watch them once in the evening and again in the morning before class. You will be working on practicing HTML in your Morning Exercise.

HTML Video 1

HTML Video 2

Hungry for More
Triangles
Write a loop that console logs a right isosceles triangle made of '#' that has the height and length of the argument.
Ex: argument is 7

#
##
###
####
#####
######
#######
Write a loop that console logs an upside down right isosceles triangle made of '#' that has the height and length of the argument.
Ex: argument is 6

######
#####
####
###
##
#
🔴 The commit message should read: 
"Commit 10 - Triangles answered"
Find the Median
Find the median number in the following nums array, then console.log that number.
hint if you check the length of the array / 2, you might get not get a whole number. In which case, look into Math.floor( // something )
const nums = [14,11,16,15,13,16,15,17,19,11,12,14,19,11,15,17,11,18,12,17,12,71,18,15,12];

Expected output:
=> 15
🔴 The commit message should read: 
"Commit 11 - Find the Median answered"
Still Hungry?
Finish the questions from the morning lab

Finish the questions from the afternoon lab

Finish the morning exercise

🔴 The commit message should read: 
"Commit 12 - Hungry for More: I tackled..."
Reminder
Remember to submit an issue to our class repository with your work by 10 am Eastern tomorrow morning! Need a reminder on how to submit? Check out the link in your class wiki.

