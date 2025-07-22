[![Open in Codespaces](https://classroom.github.com/assets/launch-codespace-2972f46106e565e64193e422d61a12cf1da4916b45550586e14ef0a7c637dd04.svg)](https://classroom.github.com/open-in-codespaces?assignment_repo_id=19970873)
# Lab 10 - TacoStand + Selection/Branching

# Create a Taco Stand Inventory Management Program!

_Learning Objective: demonstrate an understanding of decision making through branching. Be able to read existing code and upgrade it with conditional statements._

 

# Lab Prompt:

MiraCosta students want to start their own restaurant and were able to get permission to set up a pop-up taco stand on campus. One CS111 student started the program, but was struggling with how to make the program more flexible in making decisions so they passed it on to you!

They set up the proper skeleton of the program, but left `//TODO`'s for where to upgrade the existing code with branching.  Your goals are to:

- Upgrade the `TacoStand` class so it aligns with what the previous student envisioned. It already has the following:
1. an `orderSupplies` static method
2. an `areTacosAvailable` static method
3. an `updateTotalFunds` static method
- Additionally, the `Main` already has the following methods:
1. a `takeOrder` static method
2. a `printConfirmation` static method
3. a `main` method

The final version should look like the example below for this specific input (it should work appropriately for other inputs as well):

    OPENING UP THE STAND...
    ----------------------------------------
    MCC Taco Stand Status
    ----------------------------------------
    Funds Available:       $5.00   
    ----------------------------------------
    # of Asada Left:        5 tacos
    # of Pollo Left:        5 tacos
    # of Lengua Left:       5 tacos
    # of Ultimate Left:     5 tacos
    ----------------------------------------


                Welcome to MCC Taco Stand!
                    ┈┈┈┈╭╯╭╯╭╯┈┈┈┈┈
                    ┈┈┈╱▔▔▔▔▔╲▔╲┈┈┈
                    ┈┈╱┈╭╮┈╭╮┈╲╮╲┈┈
                    ┈┈▏┈▂▂▂▂▂┈▕╮▕┈┈
                    ┈┈▏┈╲▂▂▂╱┈▕╮▕┈┈
                    ┈┈╲▂▂▂▂▂▂▂▂╲╱┈┈


    Menu options:
    ----------------------------------------
    1. Carne Asada (Steak)   [$ 2.50]
    2. Pollo Asado (Chicken) [$ 1.75]
    3. Lengua (Beef Tongue)  [$ 3.00]
    4. Ultimate Taco         [$18.00]
    ----------------------------------------
    Enter choice> 1
    Enter number of tacos you want> 3
    Here you go, buen provecho!
    🌮🌮🌮

    --------CART IS CLOSED---------

    ----------------------------------------
    MCC Taco Stand Status
    ----------------------------------------
    Funds Available:       $12.50  
    ----------------------------------------
    # of Asada Left:        2 tacos
    # of Pollo Left:        5 tacos
    # of Lengua Left:       5 tacos
    # of Ultimate Left:     5 tacos
    ----------------------------------------

Errors described in the methods should react appropriately, such as ordering beyond the cart's capacity:

    Enter choice> 3
    Enter number of tacos you want> 10
    We don't have that many tacos, sorry! Try again :(
    --------CART IS CLOSED---------

    ----------------------------------------
    MCC Taco Stand Status
    ----------------------------------------
    Funds Available:       $5.00   
    ----------------------------------------
    # of Asada Left:        5 tacos
    # of Pollo Left:        5 tacos
    # of Lengua Left:       5 tacos
    # of Ultimate Left:     5 tacos
    ----------------------------------------


# Lab Instructions:

Complete each step together as a class, we'll be checking in several times within the lab! Make sure you watch the clock.

# Step 0: What do we have?

- Do an inventory on what you're given in lab
- Compile/run code:
  - Does it compile? If not, what's breaking it?
  - Does it run and crash? If so, what line is causing the crash?
  - Does it run and give the desired output? What is the desired output?

# Step 1: Constants

- Read through `TacoStand` and identify literal values that would make good constants
- Upgrade your code so it uses those constants!

# Step 2: `TacoStand.orderSupplies`

- Create a flowchart for this upgraded method, based on the documentation 
- Determine how to test the upgraded code, what values would you use to show the branches?
- **CHECK-IN** w/ group near you, compare flowcharts and test ideas. What branching statement should be used?
- Write the code and test it!

# Step 3: `TacoStand.updateTotalFunds`

- Create a flowchart for this upgraded method, based on the documentation
- Determine how to test the upgraded code, what values would you use to show the branches?
- **CHECK-IN**, compare flowcharts and test ideas. What branching statement should be used?
- Write the code and test it!

# Step 4: `TacoStand.areTacosAvailable`

- Create a flowchart for this upgraded method, based on the documentation
- Determine how to test the upgraded code, what values would you use to show the branches?
- **CHECK-IN**, compare flowcharts and test ideas. What branching statement should be used?
- Write the code and test it!
- _HINT: you'll need to add code somewhere in_ `Main` _class to test this one!_

# Step 5: `Main.printConfirmation`

- Create a flowchart for this upgraded method, based on the documentation
- Determine how to test the upgraded code, what values would you use to show the branches?
- **CHECK-IN**, compare flowcharts and test ideas. What branching statement should be used?
- Write the code and test it!

**Hacker Challenge:**

Allow the user to place multiple orders (while staying within the boundaries of what we've covered in class so far), keeping the appropriate error checking!

