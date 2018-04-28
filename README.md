Problem statement: It is important for people starting a weightlifting program to know what they’re estimated maxes are for a given number of reps.  For this project, I will create an application that will calculate a user’s estimated max weight for repetitions of one through ten using five of the most well-known formulas.

Proposed solution: Create a Windows-forms application that will calculate perceived weightlifting maxes for repetitions of one through ten using five of the most well-known formulas based on the user’s input.

Approximate timeframe: March 17th – May 5rd, 2018

Estimate of resources: Developer time from one developer 10 hours a week for about 7 weeks.

Approval Authority: Jason Jenkins

Technical Design – 
•	Version control system: GitHub
•	Language: C# 7
•	Framework: .NET 4.6.1
•	IDE: Visual Studio 2017
•	Data Store: None/NA
•	Application Type: Windows Forms Application

Functional Requirements
•	User shall be able to input repetitions of one through ten.
•	User shall be able to input weight lifted of a given repetition of one through ten (i.e., 100 pounds was lifted for 10 repetitions).
•	User shall be able to select kilograms or pounds for weight lifted.
•	System shall calculate perceived maxes using the four well known weightlifting formulas where (r) is the number of repetitions performed and (w) is the amount of weight lifted: 
o	Lombardi – 1RM = w(r^0.10)
o	Brzycki – 1RM = w(36/(37-r))
o	Epley – 1RM = w(1 + r/30) 
o	O’Connor - 1RM = w(1 + r/40)
•	System shall average the results from each formula and provide that number.
•	System shall display results in table format with: 
o	Columns of: Rep Max (RM), Average, Lombardi, Brzycki, Epley, O’Connor.
o	Rows for repetitions of one through ten (1-10).

Non-functional Requirements
•	The application shall be programmed using C#.
•	The application shall be programmed using the Visual Studio Integrated Development Environment (IDE) Windows Form Application.
•	The application shall utilize support and encourage open source development by being available on GitHub.
•	The application shall be designed with a high level of usability (i.e., easy for anyone to use with little or no training required).

