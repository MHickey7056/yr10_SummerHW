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

```
Because computers can only read 1's and 0's as on or off.
```
###2 - How would we represent the number 147 in binary? *(1 mark)*
```
001100010011010000110111
```
###3 - Can you convert the hexadecimal number **b5** to denary, there is a mark for you working. *(2 marks)*
```
181
```
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
Variable
```

(b) What type of data is returned by this function? **(1 mark)**
```
Either True or False
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
line7
```

(b) What is meant by a **syntax** error? **(1 mark)**
```
where the computer doesn;t understand what to do.
```

(c) Identify a logical error in the program and suggest how this might be fixed. **(2 marks)**
```
where the computer runs the program but is different from what the programmer intended.
```

(d) Describe and give an example of the 3rd kind of programming error. **(2 marks)**
```
run-time error, when the computer tries to complete the program but crashes during it.
```

##Algortithms
###7 - Write an **algorithm** that if given a list of numbers could find the largest. Try to use [pseudocode](http://filestore2.aqa.org.uk/subjects/AQA-GCSE-COMPSCI-W-TRB-PSEU.PDF).
```
answer here
```

##Networking
###8 - Research the following methods (*topologies*) for connecting devices to a network. In each case give a description and at least 1 advantage and 1 disadvantage.

**Bus Topology (6 marks)**
```
Describe: In a bus topology, all the servers, workstations and printers are joined together to one cable (the bus).At the end of each cable, there is a terminator fitted to stop signals reflecting back down the bus.

Advantages: Very cheap and easy to install.

Disadvantages: Every workstation on the network sees all of the data on the network making this a security risk.
```

**Ring Topology (6 marks)**
```
Describe: In a ring network each device e.g. printer, workstation and server is connected to 2 other devices, this creates a ring for signals to travel around.Every packet of dara on that network travels in only one directions and each device revieves each packet in the order of the circle until the destination device reveives the data.

Advantages: This type of network can transfer data very quickly, even if there is a a lot of devices conected since the data only tracels in one direction, so there will not be any clashes in data.

Disadvantages: If the main cable were to fail or break or even any of the devices have a fault, the entire network would crash.
```

**Star Topology (6 marks)**
```
Describe: In a star network, every device in the network has its own cable that connects to a hub or switch. A switch only sends a acket of data to the destination device, however a hub sends every packet of data to every device.

Advantages: High performance and if one cable fails the other cables will still work.

Disadvantages: Very expensive, costs a lo of money with extra hardware and if one switch or hub fails all of the other devices will have no network connection.
```
