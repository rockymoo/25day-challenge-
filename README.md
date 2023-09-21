A repository containing a detailed documentation of the activities in the system verilog progarm 

-author: Rakesh(Rakesh H R),[rakeskumar99722@gmail.com]

# 25day-challenge-
SYSTEM-VERILOG status quick links:-
1.[DAY 0](https://github.com/rockymoo/25day-challenge-#day-0)
2.[DAY 1](https://github.com/rockymoo/25day-challenge-/blob/main/README.md#day-1)


## DAY 0
 ### VERILOG DATA TYPES 
#### What values do variables hold 
almost every data types can have on of the four different values 
0 -> logic zero, false condition.
1 -> logic 1, true condition .
x -> unkown logic( 0 or 1 dont known condition) .
z -> high impedance state (between 0 and 1 state) .



### nets and variables
nets are used to connect hardware entities like logic gates and hence do not store any value on its own .
wire is popular net and widely used one 
if multiple wires connected seprately that can bunched together 
such entites with width more than one are called vector and width one is called scalars 



wire [3:0] m0; // 4bit also a vector 




#### verilog string types example 1
in given example below "system verilog" string type which 14bytes in lengeth where str1(14 bytes) completely display , str2(7bytes) only lsb part ie verilog is diplayed ,str3(20bytes)
completely displayed but msb part ie 6 bytes is empty if filled with zeros.
![STRINGDATATYPE](https://github.com/rockymoo/25day-challenge-/assets/126293037/1b321428-9ebb-4d1d-af8c-9f3d7b397909)



#### string with compare example 2



![stringtypewithcompare](https://github.com/rockymoo/25day-challenge-/assets/126293037/cdf0d0b5-082b-4a15-86e6-b17a1cffdcc3)



## DAY 1
