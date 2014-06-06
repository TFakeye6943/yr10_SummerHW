#Exam Questions <img src="../../Resources/exam.png" width=50px alt="Tick Sheet">

##Instructions
Edit this document and answer the questions in the sections surrounded by ```.

There are 30 marks available and are awarded grades as follows:

|Score|Grade|
|-----|-----|
|<6|U|
|6+|G|
|9+|F|
|12+|E|
|15+|D|
|18+|C|
|21+|B|
|24+|A|
|27+|A*|


##Data Representation

###1 - Why do we represent data using binary when using computers *(1 mark)*

answer here
We Use Binary To represent data when using computers because it is basically telling the computer to do two things instead of lots of things making it easier for the computer, and thus making the computer work quicker


###2 - How would we represent the number 147 in binary? *(1 mark)*
```
answer here
```
###3 - Can you convert the hexadecimal number **b5** to denary, there is a mark for you working. *(2 marks)*

answer here
115

###4 - Here is a function written is **pseudocode**.
```
FUNCTION validUser (users , user)
    FOR x <-1 to LEN(users)
        IF users[x] = user
			RETURN True
		ENDIF
	ENDFOR
	RETURN False
ENDFUNCTION
```

(a) What type of data is **users**? **(1 mark)**
```
answer here
Users is a boolean data
(b) What type of data is returned by this function? **(1 mark)**
```
answer here
```

##Errors
###6 - This program is supposed to find the mean of a list of numbers and print it out for the user:
```
line1:		tot <- 0
line2:		nums <- [1,6,4,2,5,3]
line3:		FOR x <- to LEN(nums)
line4:			tot <- nums[x]
line5:		ENDFOR
line6:		mean <- tot
line7:		OUTPT mean
```

(a) On which line is there a **syntax** error? **(1 mark)**
```
answer here
line 4 because it needs be tot=tot<-nums[x]
(b) What is meant by a **syntax** error? **(1 mark)**
```
answer here
a syntax error is a error where something is wrong with the way the way the code is written e.g spelling mistakes

(c) Identify a logical error in the program and suggest how this might be fixed. **(2 marks)**
```
answer here
```

(d) Describe and give an example of the 3rd kind of programming error. **(2 marks)**
```
answer here
```

##Algortithms
###7 - Write an **algorithm** that if given a list of numbers could find the largest. Try to use [pseudocode](http://filestore2.aqa.org.uk/subjects/AQA-GCSE-COMPSCI-W-TRB-PSEU.PDF).
```
answer here
import time
ListOfNumbers=[-1234567891010987654321,1230,1123,211,55.655006,1006500,34,1,1.000000001,1.1,6,15,-648778,2,2.90]
print(ListOfNumbers)
SORTED=False
while SORTED==False:
    SORTED=True
    for x in range(len(ListOfNumbers)-1):
        if ListOfNumbers[x]>ListOfNumbers[x+1]:
            SORTED=False
            temp=ListOfNumbers[x]
            ListOfNumbers[x]=ListOfNumbers[x+1]
            ListOfNumbers[x+1]=temp
            largestnumber=(ListOfNumbers[1])

print(largestnumber)
time.sleep(1)
print("Is The Largest Number")
            


##Networking
###8 - Research the following methods (*topologies*) for connecting devices to a network. In each case give a description and at least 1 advantage and 1 disadvantage.

**Bus Topology (6 marks)**
```
Describe: A bus topology is a type of network setup where each computer and network device is connected to a single cable
Advantages:
Easy To Increment
Cheap To install
Disadvantages:
If the main cable fails the network will fail
**Ring Topology (6 marks)**
```
Describe:

Advantages:

Disadvantages:
```

**Star Topology (6 marks)**
```
Describe:

Advantages:

Disadvantages:
```
