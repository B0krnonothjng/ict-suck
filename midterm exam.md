GET temperature from THERMOMETER
if temperature < 18
  SENT "Cold, the perfect temperature for sleep is 18-21 degrees"
  end if
else
  if temperature < 21
    SENT "Perfect!" to DISPLAY
    end if
  else
    SENT "No!, the perfect temperature for sleep is 18-21 degrees."
