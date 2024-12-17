# Direct Instance Variable Modification in Ruby

This example highlights a common coding practice in Ruby that can sometimes lead to issues.  While it is perfectly valid to modify instance variables directly using `instance_variable_set`, this bypasses the intended encapsulation and access methods of a class. 

In larger, more complex projects, this direct manipulation can make debugging significantly harder and may introduce unexpected behavior.