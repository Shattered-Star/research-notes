# QR-based attendance system
- students will have a qr code directly printed on their ID. this qr code will contain their LRN.
	- this will make attempts at faking the qr code much harder since it is directly printed on their id
- the qr code will be scanned every morning when they enter the school
	- security guards can be the ones scanning the student's ID
	- this would make attempts at faking the qr code much harder but 
- the qr scanner will forward the lrn to the program
- the program will mark

#### General logic of the program
- check if new day
- if yes, mark all students as absent for the day

- once scanned
- based on the lrn, mark the student as present
	- if late, mark as late
- greet the student with their name, to confirm they scanned correctly
	- if absent yesterday, remind student to get admission slip from guidance office

#### Other features
- export database to a properly formatted spreadsheet
- flag students who have a streak of being late
- other shit but my brain is hungy


#### Cons
- ***Needs a QR scanner***
- Requires a fuck-ton of time to get the program working
	- More or less 2 months
- Needs a computer (or a phone but not sure) for the demo
	- a phone might work as a substitute using the termux vm.
	- disadvantages for using termux is that im not experienced in linux
	- im also not sure if python works exactly the same on linux as it would on windows
	- further complications are brought by termux not being your conventional linux machine since its running on an android phone

### Pros
- ***Cheap*** (compared to other research projects)
- Does not require a lab
- Can be done at home

### 

#### Alternative solutions to the same problem
The all follow generally the same logic as the qr system:
- Using android applications. A computer at the school will constantly send signals in a certain radius and once confirmed that the application on the students phone has replied it will mark the student as presentt.
	- Pros:
		- Automatic 
		- Fancy
	 - Neutral:
		- need to code an android app which I have no knowledge
		- fiddling with server stuff
	- Cons:
		- needs a server
		- there might be privacy issues
		- there might be compatibility issues (not really much of a problem since ***all we need is a working prototype*)
- Using biometrics. basically the same thing as qr but almost impossible for students to fake.
	- Cons:
		- not sure about the cost but I doubt it will be cheap