# Unexpected Behavior When Directly Modifying Instance Variables in Ruby

This example demonstrates a potential issue in Ruby when directly manipulating instance variables using `instance_variable_set` instead of using accessor methods. This can lead to unexpected behavior and undermine the principles of encapsulation. 

The `bug.rb` file contains code that shows this issue, while `bugSolution.rb` provides a solution using accessor methods to maintain proper encapsulation.