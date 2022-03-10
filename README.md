# diagrame
build diagrame with Python

-------------------------------

import matplotlib.pyplot as plt
import numpy as np

#y=x^2-3x+4

x=np.arange(-5,5,0.5)

y=[]

for i in x:
    
    y.append(i**2-3*i + 4)


plt.plot(x,y,'r-')

plt.show()




