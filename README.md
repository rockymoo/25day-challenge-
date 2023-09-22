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




### 1 example  verilog string types
in given example below "system verilog" string type which 14bytes in lengeth where str1(14 bytes) completely display , str2(7bytes) only lsb part ie verilog is diplayed ,str3(20bytes)
completely displayed but msb part ie 6 bytes is empty if filled with zeros.
![STRINGDATATYPE](https://github.com/rockymoo/25day-challenge-/assets/126293037/1b321428-9ebb-4d1d-af8c-9f3d7b397909)

string type execution each char in seprate using "foreach" 
![stringline](https://github.com/rockymoo/25day-challenge-/assets/126293037/b0f22fc8-1f36-403c-920d-25117a189fdf)



### 2 example string with compare 

in given example compare(>,< ) and also multiplication {3{_______}} are used 

![stringtypewithcompare](https://github.com/rockymoo/25day-challenge-/assets/126293037/cdf0d0b5-082b-4a15-86e6-b17a1cffdcc3)

#### compare types

![stringcampareall](https://github.com/rockymoo/25day-challenge-/assets/126293037/fffebd44-e7ef-4cc2-875e-2a66fa227750)

### system verilog integer 
in 2-state integer 
#### integer
          integers are numbers without fractional part or they are whole numbers, in system verilog has 3 type integers 
          shortint (-32768 to 32767)
          int  (-2147483648 to 2147483647)
          longint(-4294967298 to 4294967297)
          the signed and unsigend can be explicitely defined 

### sigend int types
![signedinteger](https://github.com/rockymoo/25day-challenge-/assets/126293037/dc8bf755-a5d9-4542-9cdf-10bf054c1377)

### unsigend int types
![unsigenedinteger](https://github.com/rockymoo/25day-challenge-/assets/126293037/e13bbf42-d589-4f74-99d9-70d3b25bc400)


## DAY 1
