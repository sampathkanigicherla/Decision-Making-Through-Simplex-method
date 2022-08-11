# Decision-Making-Through-Simplex-method
 an approach to solving linear programming models by hand using slack variables, tableaus, and pivot variables as a means to finding the optimal solution of an optimization problem
 To slove linear programming problems. simplex method is the best way of approuch to find optimised solution for the linear programming problem 
 for implementing simplex method excell is the best way of approuch. 
 to implement the simplex method in excell some steps should follow those are
 1. Before attempting to solve a linear programming problem with Excel, make sure that the "Solver" add-in has been activated. See the Excel Add-Ins web page for details.
 2. Enter all data from the problem into cells.
 3.  The format below is acceptable but not required (Excel doesn't care where you put things, but you do have to tell the Solver program where key elements are located).
 4. Notes:include separate cells for both the values and objective coefficients of the decision variables.objective coefficients are the numbers in the objective function'values' represent the actual values of the decision variables. Initially, the "values" are normally set to zero.
 5. After solution, Excel will place the optimal decision variable values in the value cells.include one cell in which profit is computed from the decision variable values and objective coefficients (easiest with a sumproduct function--click here for explanation).include cells in which the total quantity used of each constraint is calculated, i.e., the constraint's left-hand side (again, easiest with a sumproduct).careful use of absolute cell references will allow you to enter just the first formula, then copy it to the remaining rows--see Example below.
 6. include cells that contain the right-hand side of each constraint.you may optionally include cells for constraint type (<=, >=, or =). Doing so is encouraged to make your spreadsheet more readable and to remind you of the constraint types, but these cells are not used by the solver.do not include non-negativity constraints on the spreadsheet (non-negativity is handled under Solver Options).
