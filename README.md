# Ruby NoMethodError: Unexpected Behavior with Getters

This repository demonstrates a common source of confusion for beginners in Ruby: the lack of automatic setter methods when only defining a getter.  The `bug.rb` file showcases the issue, where attempting to assign a new value to an instance variable using the getter method throws a `NoMethodError`.

The solution, shown in `bugSolution.rb`, involves explicitly defining the setter method (`value=`).