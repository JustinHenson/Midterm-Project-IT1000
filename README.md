# Home Page
## Hello, my name is Justin Henson
I am a **Junior** at Mizzou, currently working towards getting a Bachelors in Information Technology.
Below is a list of links used to navigate this site to explore some information about myself, and what I am about. I hope you enjoy learning more about who I am and what I am involved in!

- [Information About Me](./AboutMe.md)
- [Code Samples](./Code_Samples.md)
- [My Hobbies](./Hobbies.md)
- [My Goals](./Goals.md)

AboutMe.md
# **About Me**
## Who am I?
If you didn't catch it already, my name is _Justin Henson_ and I go to school at Univeristy of Missouri, Columbia, currently pursuing a Bachelors in Information Technology.
## What I do outside of school
When I'm not doing school work I can be found working at Best Buy. I work anywhere from 2 to 5 days a week. I recently got put into a new postion at Best Buy working in the precinct of GeekSquad, where I work on client's computers and help resolve any issues people may have on their personal devices. It has been a great way for me to become more comfortable on computers and learn all kinds of new skills. I hold another job at the high school I attended, where I teach the drumline, as well as run all the sound for the group. I have been playing music for 13 years now, and I find it rewarding to be able to give back to a program that did so much for me when I was in school. Besides work, I enjoy playing disc golf with friends, making music, and spending some alone time playing games.

[Go back to home page](./README.md)

Hobbies.md
# **My Hobbies**
## **_Music_**
I have been playing music since I was **8 years old**, and it has been a passion ever since. Throughout my experience within music, I picked up Bass Guitar, Guitar, Piano, and a little bit of drumset. I grew up learning Jazz, and was very involved in the jazz program at my high school, and have been apart of several jazz groups where I was lucky enough to go play at several events for my school, and have been able to play at [The Gem Theatre](https://americanjazzmuseum.org/content/gem-theater-rental) in Kansas City. Since graduating high school I haven't had as many oppurtunties to play out, but I always I hop on the chance to jam with some friends.

## **_Building Computers_**
When I was a kid I was so fascinated by computers, and wanted to figure how they worked. Fast forward to my junior year of high school and I was taking an AutoCAD class, and I enjoyed it so much I talked to my parents into allowing me to build my own PC. Since then I have helped a number of my friends build their own systems, and have learned so much about the technology that is on the market right now.

## **_Wood Working_**
The idea of being able to build something yourself that is functional, attractive, and will last, excites me. I got experience with wood working when I was in middle school, my older brother wanted to customize one of his guitars, so it became a project that my dad, brother, and myself, worked on together. It was so much fun, and it opened my eyes to a whole new world of possibilities. As of recently I built a two-level TV stand for my room, so I had space for my speakers and game consoles underneath my TV. There is so much to learn, but at the end of the day it is just a hobby of mine, and I am in no rush to master the craft.

[Go back to home page](./README.md)

Code_Samples.md
# Code Samples
### Below are some code samples that I have written:
# Example 1
```html
<!DOCTYPE html>
<html>
<head>
<meta charset="UTF-8">
<title>Fizz Buzz</title>
<script>

function fizzbuzz() {
	var display = document.getElementById('display');
	var displayHTML = "";
	for (i = 0; i < 100; i++) {
		displayHTML += "<p>" + i + "</p>";
	}
	display.innerHTML = displayHTML;
}

</script>

</head>

<body onload="fizzbuzz()">
<div id="display">

</div>
</body>

</html>
```
# Example 2
```python
import math
choice='y'
while(choice=='y'or choice=='Y'):
   radius=float(input("Enter the radius:"))
   while(radius<0):
       print("Negative radius is invalid")
       radius=float(input("Enter the radius again :"))
       print("The value entered is invalid, please input a numerical value.")
   else:
      height=float(input("Enter the height:"))
   while(height<0):
       print("Negative height is invalid")
       height=float(input("Enter the height again :"))
   volume=(math.pi)*pow(radius,2)*height
   print("Volume of the cylinder: ",volume)
   choice=input("Do u want to continue for another calculation if yes enter[y] else enter any key to exit:")
```
[return to home](./README.md)

Goals.md

# My Goals
### Here are a list of goals that I have set for myself for this semester.
- End the semester with a **_3.5 GPA_**
- Go to the gym at least **3 times a week** starting in November
- Write a piece of music for drumline
- Read a book before the new year
- Go and see a concert before the year ends

These are some goals that I have made for myself since Fall semester started, and I work towards them everyday. I have found that setting goals for big things like school grades, or small things like going to see a concert, help me achieve a better balance in my life.

[return to home](./README.md)

