*Daniel Zhou*

### Overall Grade: 79/85

### Quality of report: 10/10

* Is the homework submitted (git tag time) before deadline?

    Yes

* Is the final report in a human readable format html?  

	  Yes 
	
* Is the report prepared as a dynamic document (Jupyter notebook) for better reproducibility?

	  Yes. 

* Is the report clear (whole sentences, typos, grammar)? Do readers have a clear idea what's going on and how are results produced by just reading the report?

	Yes. The report is clear and easy to follow.
 
### Correctness and efficiency of solution: 55/55

* Q1 - N/A

* Q2 (10/10 pts) 
	
* Q3 (10/10 pts)

* Q4 (10/10 pts) 

* Q5 (15/15 pts)

* Q6 (10/10 pts) 


### Usage of Git: 4/5

* Is the hw submission put into the `master` branch? 

    Yes

* Are there enough commits? Are commit messages clear? 

    Commits should be clearer. "updating hw1 solutions" is not clear enough. `=1`.

* Is the hw1 submission tagged?

    Yes.

* Are the folders (`hw1`, `hw2`, ...) created correctly?

    Yes.	

* Do not put a lot auxillary files into version control.  

    Yes.
		

### Reproducibility: 5/5

* Are the materials (files and instructions) submitted to the `master` branch sufficient for reproducing all the results? 

    Yes

* If necessary, are there clear instructions, either in report or in a separate file, how to reproduce the results?  

    Not applicable for hw1.


### Julia code style: 5/10

* Rule (4): 4 spaces for indenting. 
    
* Rule (6): Never place more than 80 characters on a line.

* Rule (7): Always include a single space after a comma. 

    Q6.1 - missing a space between  A = UpperTriangular(randn(T,(n,n)))

    Q6.2 - missing a space between A = UpperTriangular(randn((n,n)))

    Q6.3 - missing a space between A = UnitLowerTriangular(randn(T,(n,n)))
B = UnitLowerTriangular(randn(T,(n,n)))

    Q6.4 - missing a space between A = UnitUpperTriangular(randn(T,(n,n)))

    Q6.6 - missing a space between B = randn((n,n))

* Rule (8):  Never insert a space before a comma.

* Rule (9): Always insert a single space before and after an operator, except for the `^` and `:` operators, which never have spaces around them.

* Rule (12): When naming variables or functions, use short lowercase names if possible.

* Rule (13): If a variable or function name is too long to be read in all lowercase, insert underscores at word boundaries.

* Rule (16): When naming constants, use all caps.
