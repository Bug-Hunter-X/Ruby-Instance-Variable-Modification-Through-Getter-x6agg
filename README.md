# Ruby Instance Variable Modification Through Getter

This example demonstrates a common misconception in Ruby related to modifying instance variables through getter methods.  In Ruby, getter methods only provide access to the variable's value, not a means of modification.

The `bug.rb` file shows the problem:  Assigning a new value to the getter method does not change the internal state of the object. 

The `bugSolution.rb` provides a corrected implementation using a setter method.