# in-class-activities
## Devlogs
### W1

When I remove the camera from cat, the camera will not follow the cat when game playing. Because after moving out, the Camera becomes an independent object.
https://qingw7.itch.io/week1


### W2
1. Because the color values r, g, b in Unity are decimal numbers ranging from 0 to 1, using float allows the color to change gradually. Integers can only represent whole numbers, booleans can only represent true or false, and strings are text.
2. Because _bounces is used to record how many times the ball has bounced. The number of bounces is an integer and does not require decimals, so the int data type is the most appropriate choice.
3. This error indicates that when modifying variables, one must use the correct operators and syntax.

### W3
Activity 1:
  1. I think this method can take the player's liking for the character as a numerical input, such as an int or a float, and then use a bool to   indicate whether the player knows the character's secret. Since this method ultimately needs to return the character's words, the return type   should be a string.
  2.The input of this method can be the player's current sanity value. I think using float is more appropriate as it can be a value ranging       from 0 to 100. This method simply changes the brightness of the light and does not need to return anything, so the return type should be void.
  3.This method can take the player's key-pressing time as the input. I think we can use float. Since all we need to do at the end is to          determine whether the player has accurately hit the beat, the output should be bool, which is either true or false.

Activity 2:
  I think the relationship between "class" and "component" is similar to that between a Lego instruction manual and Lego itself. The instruction manual specifies exactly where each part must be placed and which part must be used. Component refers to Lego parts and tools.
  
Activity 3:
  This is because each time there is a collision, the code multiplies the color value by a multiplier based on the speed of the ball. The ball then keeps accelerating with each collision. The more collisions there are, the more the color accumulates, so in the end, it will appear very bright.

## Open-Source Assets
### W1
- Animals: https://assetstore.unity.com/packages/3d/characters/animals/animals-free-animated-low-poly-3d-models-260727 
- Low-poly environment: https://assetstore.unity.com/packages/3d/environments/landscapes/low-poly-simple-nature-pack-162153 
