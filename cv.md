# Ramazan Byoden
## Junior Frontend Developer
### Contact information:
**Phone:** 89187963977

**E-mail:** gidyakrasava@gmail.com

**GitHub:** [Gidya](https://github.com/Gidya)

# Summary
I have excellent mathematical abilities. I work at the Institute of Mechanics of Moscow State University, where I develop RealBAC. 
I am easily trained and quickly adapt to new conditions.

# Skills
* Python, C++, Javascript
* Django, MPI
* GitHub
* VScode

# Code examples
```
import numpy as np
file = open('input.csv')
out = open('output.csv', 'w')

data = np.genfromtxt(file, delimiter=',', dtype=int)
for i in range(30):
  print(np.mean(data[:, i:i+1]))
  data[0, i] = 1.5*np.mean(data[:, i:i+1])
np.savetxt(out, data, delimiter=',', fmt='%g')

file.close()
out.close()
```
