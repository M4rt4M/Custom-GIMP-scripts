# Custom-GIMP-scripts

## Declaring Variables
Use following syntax `(let* ( variables ) expressions )`, for example: `(let* ((a 1)(b 2))(+ a b))`. This declares two local variables, a and b, initializes them, then prints the sum of the two variables.

## Assigning A New Value To A Variable
Use the set! statement to change the variable's value: `(let* ( (theNum 10) ) (set! theNum (+ theNum theNum)) )`.

## Functions
Functions are declared with the following syntax: `(define (name param-list) expressions )`, where `name` is the name assigned to this function, `param-list` is a space-delimited list of parameter names, and `expressions` is a series of expressions that the function executes when it's called.

For example: `(define (AddXY inX inY) (+ inX inY) )`. Function `AddXY` tekes in variables `inX` and `inY`, and adds them together.

We don't need to worry about how to “return” the result of our function — the last statement is the value “returned” when calling this function.

## Lists

## Registering your script

# Batch processing
TBC

# References
- [GIMP documentation](https://docs.gimp.org/en/gimp-using-script-fu-tutorial.html)
- [Function reference](https://docs.gimp.org/en/gimp-function-reference.html)
- [About batch mode](https://www.gimp.org/tutorials/Basic_Batch/)

### How to find wehat you need for your script
 In GIMP go to Filter>Script-fu>Console>Browse - this opens a Procedure Browser, which gives you a detailed list of all commands.
