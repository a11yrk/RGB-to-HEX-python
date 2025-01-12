# RGB-to-HEX-python

def rgb(r, g, b):

  #ranges of values and particularly helpful in negative rgb values
  
  r = max(0,min(r,255))
  
  g = max(0,min(g,255))
  
  b = max(0,min(b,255))
    
  return f"#{r:02x}{g:02x}{b:02x}".upper().lstrip('#') 
  
  #the {} things are for the number of decimal limitation
  
    pass
