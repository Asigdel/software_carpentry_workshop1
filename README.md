# software_carpentry_workshop1
```
how to open pyhthon notebook from cmd prompt
```
```
conda update conda
conda update --all


####how to see which version of pandas#######

import pandas
pandas.__version__
exit()

####### Which directory to go ###########################

D:
D:\>dir

cd Data_carpentry
D:\Data_carpentry>jupyter notebook

```

```
%matplotlib inline
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt


```
%matplotlib inline
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt

```
```
df = pd.read_csv("D:/2-dayworkshoponDatacarpentry/python_data/inflammation-01.csv",sep=",",header = None)
df.head()

```

```
how to write a loop initialize and increment the loop

```
```
University = "FloridaState"
count = 0            # initialize the loop 
for character in University:
    count = count + len(character) # increment the loop
print(count)
#len(University)

```

