---
title: Programming a Function
subtitle: Discovering the Fun in Functions
---

When the need arises to write a function in a programming language, it can often feel overwhelming! Most people stay away from writing their own functions and often rely on other packages or modules to find an appropriate way to solve a problem.

**However, functions are not as complex as you might think!**

My lightbulb moment came when I realized how closely mathematics and programming relate to each other.

Let's first have a look at mathematical functions.

<p align="center">
  <figure align="center">
    <img src="/img/blog/writing_a_function/sin.jpg" width="228" height="228" title="www.imgflip.com" style="border: #404040 2px solid;">
    <figcaption>Source: <a href="www.imgflip.com">imgflip</a></figcaption>
  </figure>
</p>

Mathematical functions are written in the same format as programming functions. Have a look at the characteristics of the following linear function:

$$y = 5x + 2$$

* It has an input variable: $x$
* The input variable, $x$, can have any specified numerical value: Eg. $x = 4$
* It has an output variable: $y$
* the output variable, $y$, is calculated by substituting the specified value of $x$ (eg. $x = 4$) into the equation: $y = 5*4 + 2 = 22$

These characteristics are exactly the same when writing a function in a programming language, such as R or Python.

We can test this hypothesis on a standard function. In most programming languages there is usually a pre-defined `sum` function. The objective of this function is to add a series of specified numerical values. If we want to calculate $y$ by using the `sum` function, where

$$y = 1 + 0 + 2 - 3 + 5$$

we would write it as follows:


<p style="text-align: center;" markdown="1">`y = sum(input = [1, 0, 2, -3, 5])`</p>


If we run this code, a value of 5 would be assigned to `y`.

**How does the computer know what to do with these numbers?**

*The answer lies within the defined `sum` function.*

What happens in the background, is that a pre-written function, called `sum`, is used to add up these numbers. Inside this `sum` function, it might look something like this:

```  python
def sum(input):

  total = 0

  for number in input:
    total = total + number

  return total
```
The code above tells the computer what to do when the coder wants to `sum` a series of values.

**Let's examine the inner workings of this function:**

1. `def` is used to state that you want to *define* something.

2. What do we want to define? In this case, we want to *define* what the function `sum` means.

3. The brackets are used to define arguments that will be used within the function. In this case, `input` is the only argument that `sum` will accept. For the `sum` function, it is expected that `input` should be a series of numerical values.

4. `:` states that all the indented code that follows is a series of commands that should be performed when the function is called.

5. `total = 0` is the first command of our `sum` function. This is the start point for our calculation.

6. We then enter a `for` loop. The `for` loop can be interpreted as follows: *for every `number`  in the series `input`, perform the following actions*

7. We want to add each number to `total` to reach a final answer for `sum`. We do this by assigning a new value to `total` during each iteration of the `for` loop. If `input = [1, 0, 2, -3, 5]` the value of `total` would change as follows:
    - *Iteration 1*: `number = 1` which means `total = 0 + 1 = 1`
    - *Iteration 2*: `number = 0` which means `total = 1 + 0 = 1`
    - *Iteration 3*: `number = 2` which means `total = 1 + 2 = 3`
    - *Iteration 4*: `number = -3` which means `total = 3 + (-3) = 0`
    - *Iteration 5*: `number = 5` which means `total = 0 + 5 = 5`

8. The `for` loop ends after the actions have been performed for the last `number` in `input`.

9. The last command of the function, `return`, states that something should be *returned* when the `sum` function is used. In this case the final value of `total` needs to be *returned*.

10. As mentioned earlier `y = sum(input = [1, 0, 2, -3, 5])` would result in `y` being assigned a value of 5. This is because the final value of `total` within the `sum` function in this example has a value of 5 and is being *returned*.

**Let's recap on the characteristics of a function by referring to the `sum` function:**

* It has an input variable: `input`
* The input variable, `input`, can have any specified numerical value: Eg. `input = [1, 0, 2, -3, 5]`
* It has an output variable: Eg. `y = sum(input = [1, 0, 2, -3, 5]) = 5`
* the output variable, `y`, is calculated by performing the commands within the function.

This is the essence of writing a function. I hope that this has helped you in your quest in writing and understanding functions. Now it is time to apply your theoretical knowledge of functions in the real world! Enjoy!
