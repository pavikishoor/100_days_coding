## Blockly Maze Completion
After you complete the 10th level, what is the JavaScript code you got? 
Cut and paste and assign it to the variable level_10_code.

How many blocks did you have left? 
Assign it to the variable remaining_blocks.
```
# Cut and paste the JavaScript code and assign it 
# to the variable below 

level_10_code = """ while (notDone()) {
  moveForward();
  if (isPathLeft()) {
    if (isPathForward()) {
      if (isPathRight()) {
        turnRight();
      } else {
        turnLeft();
      }
    } else {
      turnLeft();
    }
  } else {
    if (isPathRight()) {
      turnRight();
    }
  }
} """




# Transfer the value from Level 10 "blocks remaining"
# to the variable below 

remaining_blocks = 0 


print("JavaScript code for Level 10")
print(level_10_code)

print("Number of blocks remaining", remaining_blocks)

```
