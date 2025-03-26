# Instructions


## Classes

<details>
  <summary>
    Part 2: Classes (50 pts)
  </summary>

  - You will define a class and use the class methods to perform operations
  - Fox example, we will define a car in this assignment
</details>

## In classes.py

We will define a class named car  
This class will have
 - three instance attributes (all private attributes)
   - make
   - model
   - color
 - one initializer method
 - one str method
 - three get methods (for each attribute)
 - three set methods (for each attribute)


<details>
  <summary>
    ✅ Create a PyCharm project
  </summary>

  - Create main.py, classes.py and part2.py
</details>

<details>
  <summary>
    ✅ Define initializer
  </summary>

  - Define the initializer method to bind all the attributes, make, model, color to the object as private attributes, you may choose attribute names
</details>


<details>
  <summary>
    ✅ Create class
  </summary>
  Create a class named car (code conventions must be followed)
</details>

<details>
  <summary>
    ✅ Define initializer
  </summary>

  - Define the initializer method to bind all the attributes, make, model, color to the object as private attributes, you may choose attribute names
</details>


<details>
  <summary>
    ✅ Define str method
  </summary>
  Define the str method to display the state of your object (choose a good format to display)
</details>


<details>
  <summary>
    ✅ Define get methods
  </summary>

  Define three different get methods to access the 
  - make
  - model
  - color 
use the minimal statements
</details>


<details>
  <summary>
    ✅ Define set methods
  </summary>

  Define three different set methods to change the values of the
  - make
  - model
  - price  
use the minimal statements
</details>


## In part2.py

### In the function class_ops(), perform the following operations

<details>
  <summary>
    ✅ 1. Cars dictionary
  </summary>
  Create a file called cars.bin. Unpickle it and store the (empty) dictionary in a variable of your choice
</details>


<details>
  <summary>
    ✅ 2. Add a new car
  </summary>

  - Using four input statements - get from user
    - car VIN
    - car make
    - car model
    - car color 
  - Create an object of the car class defined in classes.py with make, model and price
  - Add this object to the unpickled dictionary with the car VIN entered by the user as the key and the object as value
  - Add some sample cars to your cars dictionary
</details>


<details>
  <summary>
    ✅ 3. Update car model 
  </summary>

  - Get a car VIN from the user using input statement
  - If that VIN is in the dictionary
    - Display all the data about that car in a pretty format
    - Get the new model from the user, and
    - Update its model using the appropriate method
    - Display the data about the product again
</details>


<details>
  <summary>
    ✅ 4. Serialize the dictionary 
  </summary>

  - Serialize this dictionary (pickle it) and save it in the file products.bin
</details>


## In main.py

- Import class_ops
- Define main and call class_ops
- Call main

<details>
  <summary>
    ✅ Copy code to replit 
  </summary>

  - Copy this code to Exam2Prep App in the appropriate files
</details>
