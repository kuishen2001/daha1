# daha1
# Linear Programming Example---The Diet Problem
# Part 1. Documentation for the five packaged food items selected for the assignment.
The five packaged food items: whole-wheat bread, broccoli, green bean, canned chicken breast and canned tuna in water have been selected for the assignment. The prices of their serving sizes can be calculated as below:  <br>
Whole Wheat Bread Price = 5.99/32 = 0.19, Broccoli Price = 5.99/11 = 0.54, Green Bean Price = 6.99/11 = 0.64, Canned Chicken Breast Price = 11.99/21= 0.57, and Canned Tuna in Water Price = 14.69/24 = 0.61.  <br>
To calculate additional nutrients in their serving sizes not included in the labels, data on magnesium and thiamin per 100g of food item have been obtained from the FoodData Central of U.S. Department of Agriculture (https://fdc.nal.usda.gov/) for the five packaged food items, added to the notes below the attached photographs that already contain the data extracted from the labels, and subsequently converted to the values per serving size.
# Part 2. The linear programming problem in standard form.
The original linear programming problem (based on decision variables x1 = # of servings of bread, x2 = # of servings of broccoli, x3 = # of servings of bean, x4 = # of servings of canned chicken breast, x5 = # of servings of canned tuna) is to minimize cost 0.19*x1 + 0.54*x2 + 0.64*x3 + 0.57*x4 + 0.61*x5,  <br>
subject to the nutrition constraints by sodium: 170*x1 + 30*x2 + 5*x3 + 270*x4 + 270*x5 <= 5000,  <br>
by energy: 110*x1 + 30*x2 + 25*x3 + 60*x4 + 90*x5 >= 2000,  <br>
by protein: 4*x1 + 4*x2 + 4*x3 + 13*x4 + 18*x5 >= 50,  <br>
by vitamin D: 0*x1 + 0*x2 + 0*x3 + 0*x4 + 2*x5 >= 20,  <br>
by calcium: 45*x1 + 40*x2 + 30*x3 + 0*x4 + 20*x5 >= 1300,
by iron: 0.9*x1 + 0.6*x2 + 0.9*x3 + 0*x4 + 1*x5 >= 18,  <br>
by potassium: 100*x1 + 270*x2 + 180*x3 + 70*x4 + 188*x5 >= 4700,  <br>
and non-negative x1, x2, x3, x4, x5 >= 0.  <br>
Standard form (based a. non-negativity constraints for all variables, b. all remaining constraints expressed as equality constraints, and c. non-negative right hand side vector) is  <br>
to maximize the negative of cost -0.19*x1 - 0.54*x2 - 0.64*x3 - 0.57*x4 - 0.61*x5  <br>
subject to the nutrition constraints by sodium 170*x1 + 30*x2 + 5*x3 + 270*x4 + 270*x5 + s1= 5000,  <br>
by energy: 110*x1 + 30*x2 + 25*x3 + 60*x4 + 90*x5 – s2 = 2000,  <br>
by protein: 4*x1 + 4*x2 + 4*x3 + 13*x4 + 18*x5 -s3 = 50,  <br>
by vitamin D: 0*x1 + 0*x2 + 0*x3 + 0*x4 + 2*x5 – s4 = 20,  <br>
by calcium: 45*x1 + 40*x2 + 30*x3 + 0*x4 + 20*x5 – s5 = 1300,  <br>
by iron: 0.9*x1 + 0.6*x2 + 0.9*x3 + 0*x4 + 1*x5 – s6 = 18,  <br>
by potassium: 100*x1 + 270*x2 + 180*x3 + 70*x4 + 188*x5 – s7 = 4700,  <br>
and non-negative x1, x2, x3, x4, x5, s1, s2, s3, s4, s5, s6, s7 >= 0, where s1 is a slack variable and s2-s7 are surplus variables. 
# Part 3. The linear programming problem has been solved and results attached.
# Part 4. The solution for the linear programming problem.
Optimal solution is obtained, with Bean = 0.0, Bread = 10.825688 = 10.8 slice or 465.5 g, Broccoli = 15.321101 * 85 g = 1302 g, Chicken = 0.0, Tuna = 10.0 * 85 g = 850 g, and the cost (Objective) = $16.43 (pre-tax).
# Part 5. What happens when adding additional nutritional constraints magnesium and thiamin.
Adding magnesium and thiamin causes no change in the solution. No additional food item is needed. The new constraints seem to be redundant. 
