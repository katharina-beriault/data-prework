# Katharina Beriault

Hello Katharina! You have done the Prework, which is the first step here in Ironhack in such a brilliant way, congrats! Keep going and doing these kind of efforts!

## 1. Snail and the well

In this exercise, you had to deal mainly with `while` loops and `if` conditions and you understood them perfectly, congrats!

The only mistake that I found here is that you forgot to write an `if` condition before substract the nightly_distance to the snail_position. That's because if the snail didn't reach the top of the well during the day, you have to substract it, but one day the snail will reach it and it won't be necessary to substract the nightly_distance. 

Anyway, great work here, you solved every question!

## 2. Duel of sorcerers

Wow! Perfect job here! You understood how to deal with dictionaries and iterate through them. 

If you want to optimize your code, just one thing: you don't need to use the variable `tie` and all the elif where you use it.

At all, your exercise is perfect, also you used the `statistics` library and defined functions, congrats!

But take in count that when you define a function, you just have to call it with the parameter inside the parenthesis. That's an example:
```python
def mean(list_of_powers):
  n = len(list_of_powers)
  mean = sum(list_of_powers) / n
  return mean

mean(gandalf_power) #You just call the function with gandalf's powers
mean(saruman_power) # You just call the function with saruman's powers
```
## 3. Bus

Another great task here, I have anything to say, it's perfect, congrats!

## 4. Robin Hood

I'm impressed Katharina, this was such a difficult task and you solved it in a brilliant way!

Basically, in this assignment you had to deal with tuples and points of coordinates. You have used lists comprehension which has save you a lot of time and code lines, great! 

## 5. Temperature

Good work here! You had to work with operators inside `for` loops or `if` conditions and it seems that you understood it in a very good way. 

In the bonus, it's cool that you used `enumerate` but you can do that loop in an easier way as you know how to use lists comprehension: 
```python
hours_greater_than_70 = [t for t in range(len(temperatures_C)) if temperatures_C[t] > 70]
print (hours_greater_than_70)
```
Then, the first error that python shows to you is because you can't use operators in temporary variables inside a for loop. The second one is that you defined your variable above as consec_greater_70 and in this exercise you forgot "greater", that's why it doesn't work. 

Don't worry about that, it's a little mistake, the essential part you solved it perfectly!

## 6. Rock, paper, scissors

In this exercise you had to deal with functions and `while` loops inside them. Let's check it!

In question 4, to be more accurate, the correct value would be `n_rounds // 2 + 1`.

Great work defining functions during the whole assignment. It was the key topic here and you understood how to deal with it, congrats!

In questions 6 and 7 you defined the functions well but you missed to return a result, which is, in fact, the choice of the player and the choice of the computer. It would be something like this:

```python
# That's for question 6
def comp_choice(gestures):
  return random.choice(gestures)

#That's for question 7
def player_choice():
  while True:
    player_input = input("Which gesture do you want to show? ")
    if player_input == 'rock' or player_input == 'paper' or player_input == 'scissors':
      return player_input
      break
        
    else:
      print("Enter either 'rock' or 'paper' or 'scissors' to be able to play")
      player_choice()
      break
```

If you have any doubt, check this link with the difference between `print` and `return`: 
https://www.codecademy.com/forum_questions/518ffbfeb3f05c44fe001395

In the following questions you don't need to define the functions that you created before, you just have to call them as you did at the end of the cells in questions 6-9. You will save a lot of code lines. 

In exercises 10 and 11 you need to call those functions defined above properly. 

The logical thought behind your code is pretty good, but you have to check these issues with the `return` function. If you have some free time and want to try, check how to do it using return, you almost got it. 

Good work at all!
