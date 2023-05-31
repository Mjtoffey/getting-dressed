# INIT variables to be added
1. forecast -to evaluate the clothes to be worn based on temperature and other affects of weather
    
    temp- Temperature outside
    
    wthr- Rain
2. Rain Jacket - to be worn when raining
3. Hoodie - to be worn when temp <= 75
4. Tshirt - to be worn
5. underwear - to be worn
6. Bottom Layer( 
 
     Pants - to be worn when temp <=75


    shorts - to be worn when temp > 75)
8. socks - to be worn
9. shoes - to be worn

# Functions
## Prepare clothes
```
  If Matthew 
      Then + Hoodie
      END
 Check Temp => () {
  If <= 75 
    Add Hoodie, 
    use Bottom Layer (Pants)
   Else 
    use Bottom Layer (Shorts)
  END
  }
  Check wthr => () {
    If raining 
      add Rain Jacket
    ELSE
    END
  }
  ```
  ## Getting Dressed
  
  ```
  Temp is 60
  No rain
  a. Step into underwear and pull up to the waist
  b. Step into Bottom Layer(Pants) and pull up to waist
  c. Place head inside bottom of shirt and through large hole
      Place left arm through left hole
      Place Right arm through right hole
  d. repeat step c with Hoodie
  e. Sit down
  f. Grab Left sock and place over foot, then pull to fit foot
  g. Repeat step f with right
  h. Place left shoe over left foot and tie
  i. Repeat step h with right foot
  ```
  
  
