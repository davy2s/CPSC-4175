	Homework 05, CPSC-4175 				Johnathan D. Kimbro
Chapter 14, Object-Oriented and Classical Software Engineering September 7, 2017 

1.	What are the two basic ways of designing a product? Explain what they are and how they differ.  

	***Operation-oriented design and data-oriented design
	In Operation-oriented design the operations are concidered first
	In data-oriented design the data is considered first***
	
2.	What are the inputs and the outputs to the design workflow, according to the book? Briefly explain why the particular inputs are important and how they impact design. Briefly explain how the particular outputs are important and how they influence design. 
	
	***Input is what the product is to do.
	Output is how the product achieves its task.***
	
3.	Traditionally, a computer program was seen as a data processing application. Variables were divided into three categories: input variables, output variables, and processing variables. The book describes a design process based on this paradigm that is recursive. Explain in detail how you would design a student’s graduation requirements in terms of input variables, variables, and processing variables. This is not asking for a design, but just identification of variables you might want to create and where in the design you would place them. 

	***Input variables: degree ,coursesComplete***
	
	***Output variables: eligibilityForGraduation, corsesToTake, Courses, degree ,coursesComplete***
	
	***Processing variables: courseList, eligibilityForGraduation, corsesToTake***

4.	Perform a transaction analysis for the graduation requirements problem you used for the preious question. Your answer should be a sequential list of subprocedures you would design to solve the problem. Notice that the previous question called for what was, in essence, a list of nouns, while this question calls for, in essence, a list of verbs. 

	***getDegree(), getCoursesComplete(), computeCorsesToTake(), computeGraduationEligibility(),***
	***returnGraduationEligibility(), returnCorsesToTake(), returnDegree(), returnCourses(),returnCoursesComplete()***

5.	Object-oriented analysis and design conceptually is seen as a grouping of objects, instantiated from classes. Classes encapsulate both states (variables, nouns) and bejhavior (subprocedures, verbs). Based on your answers to the two previous questions, describe one class that jight be appropriate for a graduation requirements application. Identify the attributes (properties) and behaviours (methods) this class might contain. 

	***Degress()***

	***Properties: eligibilityForGraduation, corsesToTake, Courses, degree ,coursesComplete***

	***Behavior: getDegree(), getCoursesComplete(), computeCorsesToTake(), computeGraduationEligibility(), returnGraduationEligibility(), returnCorsesToTake(), returnDegree(), returnCourses(),returnCoursesComplete()***

6.	As discussed in the book, the design workflow can be considered an iterative, spiral process in itself. As we have been discussing in class, the design phase can be seen as part of an iterative that also includes analysis, implementation, and testing phases. The answer to this question obviously depends on the nature of the software under development, so there is no one correct answer to this question. Here is the question: Consider the software project you are working on for this class, and briefly state which view you think is more appropriate to your work. Justify your answer by making a reasonable argument as to why you answered this question the way you did. 

	***I believe that our design workflow has been iterative because we have not had to go back and redo anything.***

7.	What is the difference between testing an implementation and testing a design? Write a procedure for testing the design of the student graduation requirements problem in the questions above. Define a procedure for one of the following: either a data analysis design, a transaction analysis design, or an object oriented design.

	***Implementing a design is coding it testing is making sure it works.Test each function.***

8.	What is the cyclomatic complexity of figure 1? Explain your answer. 
 	***3. 2 decisions plus one.***
	
9.	Discuss one CASE tool you have previously used. If you have never used a CASE tool, find an open source CASE tool using an internet search, download and install it, complete a “Hello World” application, and discuss your experience.  
10.	Read the article “the-right-stuff.pdf” in the pdf directory. (You may find a better copy online.) Write a one paragraph appreciation of the article.  

 
