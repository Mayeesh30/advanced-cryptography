# Python3 code to implement the

# approach

import random

from datetime import datetime

# Passing the current time as the seed value

#random.seed(datetime.now())

for i in range(10):

 print(random.randint(0, 30), end="\t")

# This code is contributed by phasing17



#range(8)
#print(range(8))
for i in range(8):
  print(i)

# Python3 code to implement the
# approach
import random
from datetime import datetime
import time
import os

# Passing the current time as the seed value
random.seed((time.time_ns() + os.getpid())%20)

for i in range(40):
    print(random.randint(0, 200), end="\t")
     # advanced-cryptography
