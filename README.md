# Chemical Engineering Modeling
## Objectives -
The following is a partial list of objectives that you are expected to master by the end of this course. 

- Use python to write a simple code to find the root of an equation using the bisection method.
- Examine a Jupyter Notebook with python code and find and correct the errors.
- Read a simple python code and explain to a high school student the result of running this code.
- Using a model of diffusion in a Stefan tube, determine the rate of evaporation of a pure liquid into air.  Use python to solve the 2nd order ODE with split boundary conditions.
- Determine the rate of heat loss from an electrical wire with insulation.
- Solve for the heat loss from a slab that is heated by radiation on the opposite side.  Resolve, but this time pass additional arguments to the function using the Args command in solve_ivp.
- Perform linear and nonlinear regressions using Excel and python's SciPy Curve_fit and calculate 95% confidence limits on each parameter as well as the r^2, variance, r^2Adjusted parameters
- Given a mathematical description of a process numerically solve a momentum balance to determine the pressure drop in a pipeline for a non-newtonian fluid using both python and COMSOL.
- Use method of lines to solve a diffusion in a slab problem and the python ODE solver solve_ivp.
- Calculate the propagation of error that results in measuring the flowrate from a volume and time measurement.
- Optimize the set of equations using the stated constraints given in the Hock Schittkowski problem #71 using Excel and the python packages of SciPy, Gekko and APMonitor.
- Use spreadsheets (EXCEL), an equation-solving program (Python) and a chemical simulation program (ASPEN) to solve material and energy balance problems.
- Use spreadsheets (EXCEL), an equation-solving program (Python) and a chemical simulation program (ASPEN) to solve transport problems (Mass, Momentum, and Heat) 
- Work effectively in problem-solving teams, and carry out meaningful performance assessments of individual team members.
- Texts and Materials -
No text is required for this course.  Instead you must purchase TCLAB TCLAB is an Arduino based electronics lab that has a shield that contains two heaters, two temperature sensors, and an LED. The shield plugs into an Arduino Leonardo that includes a USB interface for real-time data. Using this equipment you will learn programming and conduct several experiments.  In future ChE classes you will learn PID tuning and advanced controls with real-time data. Starting source code and many examples are available in Python, MATLAB, and Simulink.
- We will be using the following textbooks that you have already purchased:
1. Elementary Principles of Chemical Processes, 4th Ed., R.M. Felder, R.W. Rousseau and Lisa G. Bullard, John Wiley & Sons, New York
2. Transport Processes and Separation Process Principles (Includes Unit Operations), 5th Edition, by Christie J. Geankoplis, A. Allen Hersel, Daniel H. Lepek, Prentice Hall, PTR, 2018.
3. Laptop that can run windows ChE programs:  Excel, Python, Aspen (Windows), and Comsol
## Tentative Schedule -

Week

September
9/7	

Before Class:  Complete the python tutorial given to the Spring Semester PCP II students)

Course Introduction
Cooperative Learning

Review of Felder, Rousseau and Bullard (FRB) 10.2a Transient Material Balances and solving first order differential equations given the initial conditions:  Tank drainage problem

Python ODE's and solve_ivp: FRB Example 10.2-1 Mass Balance on Tank -Template.ipynb

Python: What are functions? Print Statements and formatting; for statements, plot basics

9/12

One-Dimensional Binary Mass Transfer in a Stefan Tube
Shooting Method for Split Boundary Value Problem
Source: Cutlip & Shacham Problem 10.1

Python 

9/19	

Flow through complex pipe networks
fsolve for system of non-linear equations

9/26	

Unsteady state diffusion (python and Comsol) C&S 10.13 for a slab

Unsteady state conduction (python and Comsol) C&S 6.8 for a slab

Method of Lines and Finite Difference Equations 

10/3	

C&S 5.2 Calculation of Flow Rate in a Pipeline:

Using Args with functions (multiple parameters)
Printing Tables and Graphs with multiple parameters

Adding a Source Term:

C&S 9.2 Heat conduction in a wire with a electrical heat source.  This is different from the other 2 cases of varying area because it has a heat generation source. (python and comsol) 

C&S 9.5 Heat Loss through pipe Flanges (Fins)  (python and comsol)

10/10	

Review for Exam 1

Exam 1 on Wednesday

10/17	

Monday:  How does it work?

Root finding methods

Newton's Method, Runge Kutta for ODE's, Numerical Stability

10/24	

Regressions:  Multiple linear and non-linear

Regression Statistics

Excel:

Excel Basics

Excel Functions and Conditionals

10/31	

Excel Using Solver

Excel Solver = python fsolve

Machine Learning Basics:  Big Data

https://apmonitor.com/pds/index.php/Main/AutomotiveMonitoring

Case Study 1: Catalyst Light-Off
Case Study 2: GIS Map Visualization
Case Study 3: Fuel Efficiency Regression

11/7	

Review for Exam 2

Exam 2 on Wednesday

11/14	
AIChE Annual Meeting

Crash course in statistics (Excel and python)

Population and Sample: probability, mean, variance, covariance,
Density functions: normal probability, chi squared, t and F distributions
Confidence interval and hypothesis testing (Blah!)

Statistics for regressions (Advanced) 

propagation of Errors
variance
student's T distribution
confidence intervals

11/21	

 Statistics continued
11/28 (monday only)	

Optimization using Excel solver

12/5	Excel: ANOVA
12/12 (monday only)	Review for final Exam
12/14 Wed

Reading and Review Day – No Class

12/15 - 12/21

	Thursday-Wednesday, December 15-21 (includes Saturday, December 17

Final Exam: Comprehensive 
	

Remember to design your chemical process equipment and give them as gifts during the holidays!
