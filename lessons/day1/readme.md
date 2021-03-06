_Jumpstart Live (JSL)_
# Day 1

## Prep work
* Review your [Madlibs](https://github.com/Ada-Developers-Academy/jump-start/blob/master/lessons/09-programming-grammar/assignments/madlibs.md) solution and be prepared to talk with others about your code

## Goals
* Have a big picture idea of your own work flow and how to improve it
* Understand and be able to use Ruby style practices

## Warm up
* Walk your partner though your MadLibs code focusing on using programming vocabulary (e.g, variables, assignment, strings, input, output, string interpolation, string concatenation)

## Lessons
* [Workflow](workflow.md)
* [Ruby style](style.md)
* [Ruby types](ruby_types.md)
* [Keyboard input](keyboard_input.md)
* [Strings](strings.md)

## Exercises
1. Discuss [bad style Madlibs example](code/bad_style_madlibs.rb) 

1. How would you modify the code below to improve the code style and readability?

    ```ruby
    foods = ["shrimp", "cauliflower", "salmon", "garlic", "oysters",
    "salami", "tomatoes", "okra", "zucchini", "avocado"]
    print "\nHow many foods would you like to see? I suggest 10, but it's up to you. "
    items=gets.chomp.to_i
    if items >10
    puts "Best I can do is 10. Let's do 10."
    items=10
    elsif items >=1 && items<= 10
    puts "Ok! Let's do " + items + "."
    else
    puts "We'll just pretend you said 10."
    items = 10
    end
    puts "...Your Fancy Random Menu..."
    items.times do |i|
    y = foods[rand(0...(foods.length))]
    puts i.to_s+": "+y
    end
    ```

1. Revisit your MadLibs code, and update your code to improve its style

1. Bio Program
    * Create a program that accepts input from the user and outputs a bio with that information
    * Use up to five different attributes about the person to populate the bio
    * Output should consist of a paragraph of output created from the users input

    #### Use Case
    _Input_
    ```
    Name: Viola Davis
    Birthday: August 11th, 1980
    Occupation: Actress
    ```

    _Output_
    ```
    Viola Davis is an actress who is 50 years old.
    Her birthday is on August 11th.
    She is a(n) actress.
    ```

    #### Optional Challenge
    Use the attributes provided to do some calculations to make your bio a bit more interesting.

    _Output_
    ```
    Viola Davis is an actress who is 50 years old.
    Her birthday is 34 days from today, on August 11th.
    She is a(n) actress.
    ```

## Debrief
* What new things did you learn today?
* What topics are you still struggling with?
* What did you especially enjoy about today's class?
* What can be improved for future classes?

## Resources
* [Day 1 Videos](https://adaacademy.hosted.panopto.com/Panopto/Pages/Sessions/List.aspx?folderID=66c9e5fc-8a11-4db2-b0fe-ebc516d45071)
* [Good style madlibs](code/good_style_madlibs.rb)

## Homework
* Review your [Candy Machine](https://github.com/Ada-Developers-Academy/jump-start/blob/master/lessons/10-programming-expressions/assignments/candy-machine.md) solution and be prepared to talk with others about your code
* Review the [Conditional notes](https://github.com/Ada-Developers-Academy/jump-start/blob/master/lessons/10-programming-expressions/notes/conditionals.md) from Jumpstart
* Review the [Operators notes](https://github.com/Ada-Developers-Academy/jump-start/blob/master/lessons/10-programming-expressions/notes/operators.md) from Jumpstart
