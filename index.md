# INIT variables to be added
1. forecast -to evaluate the clothes to be worn based on temperature and other affects of weather
    temp- Temperature outside
    wthr- Rain
2. Rain Jacket - to be worn when raining
3. Hoodie - to be worn when temp <= 75
4. Tshirt - to be worn
5. underwear - to be worn
6. Pants - to be worn when temp <=75
7. shorts - to be worn when temp > 75
8. socks - to be worn
9. shoes - to be worn

# Functions
  If Matthew 
      Then Hoodie
      END
 Check Temp => () {
  If 60 
    Add Hoodie, 
    use Pants
   Else 
    use Shorts
  END
  }
  Check wthr => () {
    If raining 
      add Rain Jacket
    ELSE
    END
  }
  
  
  
