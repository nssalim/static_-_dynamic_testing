### Testing task 1:

# Carry out static testing on the code below.
# Comment on any errors that you see below.

Note that we are only looking for errors here.

**Not** any issues with, i.e.: 
Thinking that methods should be renamed or should be class level, or using string interpolation etc. 

These aren't errors but rather standards that vary from developer to developer. 

Only comment on errors that would stop the tests running.

```python

class CardGame:

# Error 1 - The if statement condition (the value we want to evaluate as true or false),should use a comparison operator.
  def check_for_ace(self, card):
    if card.value = 1:
      return True
    else
      return False
   
# Error 2 - The def (define) keyword (not dif) should be used to create a function.
# Error 3 - The parameters on the highest_card function should be separated by commas.
  dif highest_card(self, card1 card2):
  if card1.value > card2.value:
# Error 4 - The return value/argument should be declared as card1
    return card
  else:
    return card2
  


def cards_total(self, cards):
# Error 5 - The total variable looks like it should be an integer and be declared, moreover, it is referenced twice later on.
  total
  for card in cards:
# Error 6 - card value should be declared.
    total += card.value
  
# Error 7 - The variable total is likely to be an integer value, however,  to be treated as a string, it would need quotation marks.

# Error 8 - The indention of the final return should be in line with for.
    return "You have a total of" + total
  
```









