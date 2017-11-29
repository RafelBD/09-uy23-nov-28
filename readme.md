# Class 9     

# programming 101 with javaScript
* Variable
~~~js
var fruit = 'apple'; //string
var age = 10; //integer
var weight = 10.5 //float
~~~
* Datatype
  * Scalar type (who holds only one value)
    * Numbers
      * Integer (absolute number - 10)
      * Floating / Double (Fractional number 13.14)
    * Boolean (True, False)
    * String (Text)
  * Composite type (who holds mix value)
    * Array (array is zero based)
    ~~~js
    var names = ['apple', 'orange', 'banana']  
    names[0] //apple
    ~~~
    * Object
    ~~~js
    names = {name1 : 'apple', name2 : 'orange', name3 : 'banana'} 
    names['name2']   //orange
    //or
    names.name2 //orange
    ~~~
* Control flow
  * iterative
    ~~~js
    //while 
    var number = 0;
    while(number < 3 ) {
      names[number];
      number = number + 1;
    }
    //for, while, foreach  

    for (var number = 0; number < 3; number ++ ) {
      names[number]
    }
    for (number in names) {
      names[number]
    }
    ~~~
  * conditional
    ~~~js
    //if block
    if, else, else if, elseif
    if (true/false) {
       'if true';
    } else if (true / false) {
      'if this block is true';
    } else {
      'any if block is not true'
    }
    //ternary
    2 + 2 === 5 ? 'do something' : 'do other thing'
    //switch
    switch (condition) {
      case:
        //do something
      default:
        // do default things
    }
    ~~~

* Function   
  Built in Function 
  ~~~js
  name1 = 'sumon';
  name1.toUpperCase() = SUMON
  ~~~

  User Defined function   
  ~~~js
  function add (number1, number2) {
    return number1 + number2;
  }
  add(2, 3);
  add(5, 3);
  ~~~
  
* operator
  * unary
  * binary
  * ternary
~~~js
+ - * / % = > < == ===  ++ -- | 
~~~
`%` (Modulus) returns the division remainder    
`++` increse by 1    
`--` decrese by 1    
`==` equal check    
`===` identity check (equl check + datatype check)    


# Document Object Model (DOM) - Web API

* to showing something in console
~~~js
console.log();
~~~

* to showing something in dom using alert   
~~~js 
alert();
~~~   

<!-- 
* to select a id    

~~~js
var hello = document.getElementById('hello');
~~~

* to write inside html using innerHTML
~~~js
hello.innerHTML = "<h1>heading created by javascript</h1>";
~~~



 -->








