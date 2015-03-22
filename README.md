 
#Source Allies University
#TDD Workshop
##New Code Exercise
###Setup
* Java SDK 6 or above
* Intellij IDEA Community Edition
* jUnit 4

###Test Drive Creating a Calculator
* Create a Calculator class with an Add method.
* The method can take 0, 1 or 2 numbers, and will return their sum. 
* For example: “” or “1” or “1,2”.
* For an empty string it will return Zero.
* Allow the Add method to handle an unknown amount of numbers.
 
 
##Legacy Code Exercise
###Setup
* Java SDK 6 or above
* Intellij IDEA Ultimate Edition
* jUnit 4
* Mockito 1.9
* CDI: Context and Dependency Injection plugin for Intellij IDEA Ultimate Edition

###Test Drive Encapsulating a String Calculator 
* Create a String Calculator class with an Add method that takes in Strings.
* Utilize CDI to inject the String Calculator into the Calculator.
* Have the Calculator class delegate to the String Calculator class.

###Optional
* Create a Numeric Calculator class with an Add method.
* Utilize CDI to inject the Numeric Calculator into the Calculator.
* If the Add method is called with string parameters, delegate to the String Calculator; if the Add method is called with numeric parameters, delegate to the Numeric Calculator.
