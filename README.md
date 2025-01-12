# RGB-to-HEX-python

    def rgb(r, g, b):                              
    r = max(0,min(r,255))  
    g = max(0,min(g,255))  #ranges of values and particularly helpful in negative rgb values
    b = max(0,min(b,255))
    
    return f"#{r:02x}{g:02x}{b:02x}".upper().lstrip('#')    #the {} things are for the number of decimal limitation

    pass
