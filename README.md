##  QUESTION: 
###  WRITE PROGRAM WHICH:    

INPUT: ABC

OUTPUT: ABC BAC CBA BAC BCA CAB CBA CAB CBA

###  SOLUTION: 
  EACH POSITION DISPLAY FIRST

   DISPLAY THE REST WITH SWITCH THE REST CHARACTER

   THERE 2 WAYS
   1. WRITE PROGRAM TO CHECK EACH AFTER EACH FOR ANY NUMBER OF CHARACTER 
   2. SINCE THERE ARE ONLY 3 CHARACTERS WE CAN JUST DO AS MY ANSWER

##  ANSWER:  
 get input and turn to array in order to proceed in program

 return array to string and display as need

##  CODE:
~~~
input  = 'ABC'
x = input.split("")

y = x[0]+x[1]+x[2], x[0]+x[2]+x[1], x[1]+x[0]+x[2], x[1]+x[2]+x[0], x[2]+x[1]+x[0], x[2]+x[0]+x[1] 
output = y.join(",")

puts README
puts "Input  = #{input}"  
puts "Output = #{output}"
~~~

##  USAGE:
~~~
ruby permutation.rb
~~~

###  Thank you
