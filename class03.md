**Chapter 3: “Lists”**

HTML has three different ways of listing information:
1. Ordered List <ol> - This uses numbers to list
2. Unordered List <ul> - This uses bullets
3. Definition List <dl> - This uses the same method as Dictionary to list items

**Chapter 13: “Boxes”**

CSS Box Model is used for the containers that wraps the following elements within it
1. Margin
2. Padding
3. Content
4. Border
5. Height and Width

**Chapter 2: “Basic JavaScript Instructions”**

Arrays in JavaScript are Data types used to store a list of values which can be accessed each value individually.

Arrays can be created as such: var even_numbers;
even_numbers[2,4,6,8,10];

The way values are numbered in an array is such that index 0 refers to 2, index 1 refers to 4 index 2 refers to 6 and so on.

**“Decisions and Loops”**

A switch statement starts with a switch variable and each statement checks for a posssible value which run until the required value is matched. A proper syntax would be ( took the example from [https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/switch])

switch (expression) {
  case value1:
    //Statements executed when the
    //result of expression matches value1
    [break;]
  case value2:
    //Statements executed when the
    //result of expression matches value2
    [break;]
  ...
  case valueN:
    //Statements executed when the
    //result of expression matches valueN
    [break;]
  [default:
    //Statements executed when none of
    //the values match the value of the expression
    [break;]]
}

