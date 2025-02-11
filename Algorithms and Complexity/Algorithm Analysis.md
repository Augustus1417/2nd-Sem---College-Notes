An important part of computation complexity theory, which provides theoretical estimation for the required resources of an algorithm to solve a specific computational problem

#### Algorithm
- **3 Components:**
	- *Input*
	- *Steps*
	- *Output*
- We choose between different algorithms based on their *efficiency*
	- A good *metric of efficiency* is the computational complexity of an algorithm
- **Characteristics of an algorithm**
	- must take an *input*
	- must give some *output*
	- must have *definiteness*
	- must give *finiteness*
	- must give *effectiveness*

**Runtime Complexity** - compares *speed* and *space* of requirements of different algorithms

**Complexity Theory** - Also called *computational complexity*

###### Design Issues of Algorithm
- *Correctness* - does it solve the computational problem?
- *Efficiency* - how fast can it run?

Predicting the resources that the algorithm requires, such that evaluation of its suitability for various application can be done such as:
- *Memory*
- *Communication bandwidth*
- *Computer hardware*
- *Computational time*

##### Measuring Time
Factors affecting time complexity
- *machine* on which it is running
- *language* in which it is written
- *skill* of the programmer
- *instance* in which the program is being run

**Complexity** - a *device-independent* measure of how much time it consumes
###### Algorithm Analysis Methodology
- *Apriori Analysis* - amount of time a single execution will take, or the number of times a statement is executed (line by line of code)
- *Aposteriori Analysis* - determines the efficiency based on actual experiments, the study of exact time and space required for execution (whole performance)

**Frequency Count** - refers to the number of statements or steps needed by the algorithm to finish

Simple statement: 
	a = 10 (Count: 1)
	b = a * 5 (Count: 1)