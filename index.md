#Assumptions
   
   1.    Everyone starts off in underwear.
  
  2.    Everyone knows how to put the clothes on once they are assigned.

#Define Variables
  
    1.    forecast (object):  contains the following properties:
    ⁃    temperature (number): the current temperature in ferenheight
    ⁃    isRaining (boolean):  If true, it is currently raining
    2.    attire (object): contains the following properties:
    ⁃    rainJacket (boolean): If true, wear the rain jacket
    ⁃    warmCoat (boolean): If true, wear the warm coat
    ⁃    hoodie (boolean): If true, wear the hoodie
    ⁃    tShirt (boolean): If true, wear the t-shirt
    ⁃    pants (boolean): If true, wear the pants
    ⁃    shorts (boolean): If true, wear the shorts
    ⁃    socks (boolean): If true, wear the socks
    ⁃    shoes (boolean): If true, wear the shoes
    ⁃    sandals (boolean): If true, wear the sandals

#INIT Variables

    forecast.temperature = 70
    forecast.isRaining = false
    attire.rainJacket = false
    attire.warmCoat = false
    attire.hoodie = false
    attire.tShirt = false
    attire.pants = false
    attire.shorts = false
    attire.socks = false
    attire.shoes = false
    attire.sandals = false

#Functions
   
    getInputs()
      GET forecast.temperature from user
      GET forecast.weather from user


    prepareClothes()
     IF forecast.temperature < 45
        SET attire.warmCoat = true
        SET attire.hoodie = true
        SET attire.pants = true
        SET attire.socks = true
        SET attire.shoes = true
    ELSE IF forecast.temperature >= 45 AND forecast.temperature < 60
        IF forecast.isRaining
            SET attire.rainJacket = true
        END
    
        SET attire.hoodie = true
        SET attire.pants = true
        SET attire.socks = true
        SET attire.shoes = true
    ELSE
        IF forecast.isRaining
            SET attire.rainJacket = true
        END

        SET attire.tShirt = true
        SET attire.shorts = true
        SET attire.sandals = true
    END



    getDressed()
      IF attire.tShirt
        put on the t-shirt
    END
    IF attire.hoodie
        put on the hoodie
    END
    IF attire.pants
        put on the pants
    END
    IF attire.shorts
        put on the shorts
    END
    IF attire.socks
        put on the socks
    END
    IF attire.shoes
        put on the shoes
    END
    IF attire.sandals
        put on the sandals
    END
    IF attire.rainJacket
        put on the rain jacket
    END
    IF attire.warmCoat
        put on the warm coat
    END


#The Program
  
    getInputs()
    prepareClothes()
    getDressed()
  
  
