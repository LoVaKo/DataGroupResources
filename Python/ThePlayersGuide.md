# The Players Guide

## Day 1: Challenge “Hello, World!”
You open your eyes and find yourself face down on the beach of a large island, the waves crashing on the shore not far off. A voice nearby calls out, \
“Hey, you! You’re finally awake!” \
You sit up and look around. Somehow, opening your IDE has pulled you into the Mysterious Realms of Python, a strange land where it appears that you can use Java programming to solve problems. The man comes closer, examining you. \
“Are you okay? Can you speak?” \
Creating and running a “Hello, World!” program seems like a good way
to respond.

### Objective:
- Create a program in your favorite Java IDE that prints “Hello World!” to the console, and run it.

## Day 2: 1/3 - Challenge What Comes Next
The man seems surprised that you’ve produced a working “Hello, World!” program. \
“Been a while since I saw somebody program like that around here. Do you know what you’re doing with that? Can you make it do something besides just say ‘hello’?”

Build on your original Hello World program with the following:

### Objectives:
- Change your program to say something besides “Hello,World!”

## Day 2: 2/3 - Challenge The Makings of a Programmer
The man, who tells you his name is Ritlin, asks you to follow him over to a few of his friends, fishing on the dock. \ 
“This one here has the makings of a Programmer!” Ritlin says. The group looks at you with eyes widening and mouths agape. Ritlin turns back to you and continues, \
“I haven’t seen nor heard tell of anybody who can wield that power in a million clock cycles of the CPU. Nobody has been able to do that since the Uncoded One showed up in these lands.” \
He describes the shadowy and mysterious Uncoded One, an evil power that rots programs and perhaps even the world itself. The Uncoded One’s presence has prevented anybody from wielding the power of programming, the only thing that might be able to stop it. Yet somehow, you have been able to grab hold of this power anyway. Ritlin’s companions suddenly
seem doubtful. \
“Can you show them what you showed me? Use some of that Programming of yours to
make a program? Maybe something with more than one statement in it?”

### Objectives:
- Make a program with 5 System.out.println statements in it.
- Answer this question: How many statements do you think a program can contain?

## Day 2: 3/3 - Challenge Consolas and Telim
These lands have not seen Programming in a long time due to the blight of the Uncoded One. Even old programs are now crumbling to bits. Your skills with Programming are only fledgling now, but you can still make a difference in these people’s lives. Maybe someday soon, your skills will have grown strong enough to take on the Uncoded One directly. But for now, you decide to do what you can to help.

In the nearby city of Consolas, food is running short.Telim has a magic oven that can produce bread from thin air. He is willing to share, but Telim is an Excelian, and Excelians love paperwork; they demand it for all transactions—no exceptions. Telim will share his bread with the city if you can build a program that lets him enter the names of those receiving it.

A sample run of this program looks like this:

```
Bread is ready.
Who is the bread for?
RB
Noted: RB got bread.
```

### Objectives:
- Make a program that runs as shown above, including taking a name from the user


## Day 3 Challenge: The Thing Namer 3000
As you walk through the city of Commenton, admiring its forward-slash-based architectural buildings, a young man approaches you in a panic. \
“I dropped my Thing Namer 3000 and broke it. I think it’s mostly working, but all my variable names got reset! I don’t understand what they do!” He shows you the following program:

```python
System.out.println("What kind of thing are we talking about?");
Scanner input = new Scanner(System.in);
String a = input.next();
System.out.println("How would you describe it? Big? Azure? Tattered?");
String b = input.next();
String c = "of Doom";
String d = "3000";
System.out.println("The " + b + " " + a + " of " + c + " " + d + "!");
```

```python
a = input("What kind of thing are we talking about?")
b = input("How would you describe it? Big? Azure? Tattered?")
c = "of Doom"
d = "3000"
print(f"The {b} {a} of {c} {d}!")
```
“You gotta help me figure it out!”

### Objectives:
- Rebuild the program above on your computer.
- Add comments near each of the four variables that describe what they store. You must use at least one of each comment type (# and ''').
- Find the bug in the text displayed and fix it.
- Answer this question: Aside from comments, what else could you do to make this code more understandable? Are comments the best solution here? 

## Day 4- Challenge: The Variable Shop
You see an old shopkeeper struggling to stack up variables in a window display. \
“Hoo-wee! All these variable types sure are exciting but setting them all up to show them off to excited new programmers like yourself is a lot of work for these aching bones,” she says. \
“You wouldn’t mind helping me set up this
program with one variable of every type, would you?”

### Objectives:
- Build a program with a variable of all data types in python.
- Assign each of them a value using a literal of the correct type.
Use type() in combination with print() to display the contents of each variable.

For more information: https://www.w3schools.com/python/python_datatypes.asp

## Day 5 1/2-Challenge - The Variable Shop Returns
“Hey! Programmer!” \
It’s the shopkeeper from the Variable Shop who hobbles over to you. \
“Thanks to your help, variables are selling like RAM cakes! But these people just aren’t any good at programming. They keep asking how to modify the values of the variables they’re buying, and… well… frankly, I have no clue. But you’re a programmer, right? Maybe you could show me so I can show my customers?”

### Objectives:
- Modify your Variable Shop program to assign a new, different literal value to each of the 9 original variables. Do not declare any additional variables.
- Use print() to display the updated contents of each variable.


## Day 5: 2/2-Challenge - The Triangle Farmer
As you pass through the fields near Arithmetica City, you encounter P-Thag, a triangle farmer, scratching numbers in the dirt.\
“What is all of that writing for?” you ask.\
“I’m just trying to calculate the area of all of my triangles. They sell by their size. The bigger they are, the more they are worth! But I have many triangles on my farm, and the math gets tricky, and I sometimes make mistakes. Taking a tiny triangle to town thinking you’re going to get 100 gold, only to be told it’s
only worth three, is not fun! If only I had a program that could help me….” \
Suddenly, P-Thag looks at you
with fresh eyes. \
“Wait just a moment. You have the look of a Programmer about you. Can you help me
write a program that will compute the areas for me, so I can quit worrying about math mistakes and get back to tending to my triangles? The equation I’m using is this one here,” he says, pointing to the formula, etched in a stone beside him:

`Area = base x height / 2`

### Objectives:
- Write a program that lets you input the triangle’s base size and height.
- Compute the area of a triangle by turning the above equation into code.
- Write the result of the computation.
- 
To study if you find this difficult yet: https://www.w3schools.com/python/python_operators.asp

## Day 6: Challenge - The Four Sisters and the Duckbear
Four sisters own a chocolate farm and collect chocolate eggs laid by chocolate chickens every day. But more often than not, the number of eggs is not evenly divisible among the sisters, and everybody knows you cannot split a chocolate egg into pieces without ruining it. The arguments have grown more heated over time. The town is tired of hearing the four sisters complain, and Chandra, the town’s Arbiter, has finally come up with a plan everybody can agree to. All four sisters get an equal number of chocolate eggs every day, and the remainder is fed to their pet duckbear. All that is left is to have some skilled Programmer build a program to tell them how much each sister and the duckbear should get.

### Objectives:
- Create a program that lets the user enter the number of chocolate eggs gathered that day. 
- Using / and %, compute how many eggs each sister should get and how many are left over for the
duckbear.
- Answer this question: What are the total egg counts where the duckbear gets more than each sister does? You can use the program you created to help you find the answer.

## Day 7: Challenge The Dominion of Kings
Three kings, Melik, Casik, and Balik, are sitting around a table, debating who has the greatest kingdom among them. Each king rules an assortment of provinces, duchies, and estates. Collectively, they agree to a point system that helps them judge whose kingdom is greatest: Every estate is worth 1 point, every duchy is worth 3 points, and every province is worth 6 points. They just need a program that will allow them to enter their current holdings and compute a point total.

### Objectives:
- Create a program that allows users to enter how many provinces, duchies, and estates they have.
- Add up the user’s total score, giving 1 point per estate, 3 per duchy, and 6 per province.
- Display the point total to the user.

## Day 8: Challenge - The Defense of Consolas
The Uncoded One has begun an assault on the city of Consolas; the
situation is dire. From a moving airship called the Manticore,
massive fireballs capable of destroying city blocks are being
catapulted into the city. 

The city is arranged in blocks, numbered like a chessboard. You can assume its defenders are smart, so they can also move outside the city to say row -1 if needed. 

The city’s only defense is a movable magical barrier, operated by a
squad of four that can protect a single city block by putting
themselves in each of the target’s four adjacent blocks, as shown in
the picture to the right. 

For example, to protect the city block at (Row 6, Column 5), the
crew deploys themselves to (Row 6, Column 4), (Row 5, Column 5),
(Row 6, Column 6), and (Row 7, Column 5). (you may want to make a sketch of the situation on a piece of paper)

The good news is that if we can compute the deployment locations fast enough, the crew can be
deployed around the target in time to prevent catastrophic damage to the city for as long as the siege
lasts. The City of Consolas needs a program to tell the squad where to deploy, given the anticipated
target. Something like this:

```
Target Row? 6
Target Column? 5
Deploy to:
(6, 4)
(5, 5)
(6, 6)
(7, 5)
```

### Objectives:
- Ask the user for the target row and column.
- Compute the neighboring rows and columns of where to deploy the squad.
- Display the deployment instructions 

## Day 9: Challenge - Repairing the Clocktower
The recent attacks damaged the great Clocktower of Consolas. The citizens of Consolas have repaired most of it, except one piece that requires the steady hand of a Programmer. It is the part that makes the clock tick and tock. Numbers flow into the clock to make it go, and if the number is even, the clock’s pendulum should tick to the left; if the number is odd, the pendulum should tock to the right. Only a programmer can recreate this critical clock element to make it work again.

### Objectives:
- Take a number as input from the console.
- Display the word “Tick” if the number is even. Display the word “Tock” if the number is odd.
- Hint: Remember that you can use the remainder operator to determine if a number is even or odd.
- To study if you find this difficult yet: https://www.w3schools.com/python/python_conditions.asp


## Day 10: Challenge: Watchtower
There are watchtowers in the region around Consolas that can alert
you when an enemy is spotted. With some help from you, they can tell
you which direction the enemy is from the watchtower.

### Objectives:
- Ask the user for an x value and a y value. These are coordinates of
the enemy relative to the watchtower’s location. Positive x-values are east, positive y-values are north (as they would be on a normal graph)
- Using if statements and relational operators, display a message about what direction the enemy is coming from. For example, “The enemy is to the northwest!” or “The enemy is here!
  
## Day 11 Challenge 1 of 2: Buying Inventory
It is time to resupply. A nearby outfitter shop has the supplies you need but is so disorganized that they cannot sell things to you. “Can’t sell if I can’t find the price list,” Tortuga, the owner, tells you as he turns over and attempts to go back to sleep in his reclining chair in the corner.

There’s a simple solution: use your programming powers to build something to report the prices of various pieces of equipment, based on the user’s selection:

The following items are available:
```
Rope
Torches
Climbing Equipment
Clean Water
Machete
Canoe
Food Supplies
```

You search around the shop and find ledgers that show the following prices for these items: Rope: 10 gold, Torches: 15 gold, Climbing Equipment: 25 gold, Clean Water: 1 gold, Machete: 20 gold, Canoe: 200 gold, Food Supplies: 1 gold.

### Objectives:
- Build a program that will show the menu illustrated above.
- Ask the user to enter a number from the menu.
- Using the information above, use a match statement to show the item’s cost.
- To study if you find this difficult yet: https://www.w3schools.com/python/python_match.asp

## Day 11 Challenge 2 of 2: Discounted Inventory
After sorting through Tortuga’s outfitter shop and making it viable again, Tortuga realizes you’ve put him back in business. He wants to repay the favor by giving you a 50% discount on anything you buy from him, and he wants you to modify your program to reflect that. After asking the user for a number, the program should also ask for their name. If the name supplied is your name, cut the price in half before reporting it to the user.

### Objectives:
- Modify your program from before to also ask the user for their name.
- If their name equals your name, divide the cost in half.

## Day 12 Challenge: The Prototype
Mylara, the captain of the Guard of Consolas, has approached you with the beginnings of a plan to hunt down The Uncoded One’s airship. “If we’re going to be able to track this thing down,” she says, “we need you to make us a program that can help us home in on a location.” She lays out a plan for a program to
help with the hunt. One user, representing the airship pilot, picks a number between 0 and 100. Another user, the hunter, will then attempt to guess the number. The program will tell the hunter that they guessed correctly or that the number was too high or low. The program repeats until the hunter guesses
the number correctly. Mylara claims, “If we can build this program, we can use what we learn to build a better version to hunt down the Uncoded One’s airship.”

Sample Program:
```
User 1, enter a number between 0 and 100: 27
After entering this number, the program should clear the screen and continue like this:
User 2, guess the number.
What is your next guess? 50
50 is too high.
What is your next guess? 25
25 is too low.
What is your next guess? 27
You guessed the number!
```

### Objectives:
- Build a program that will allow a user, the pilot, to enter a number.
- If the number is above 100 or less than 0, keep asking.
- Clear the screen once the program has collected a good number (you can just write 50 blank lines to clear the screen :) ).
- Ask a second user, the hunter,to guess numbers.
- Indicate whether the user guessed too high, too low, or guessed right.
- Loop until they get it right, then end the program.
- To study if you find this difficult yet: https://www.w3schools.com/python/python_while_loops.asp
