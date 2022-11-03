# 2교시: KNN을 활용한 데이터 분류

https://youtu.be/6iCl5qkzYrk

## 라이브러리 및 데이터 로드 코드

* 파일 위치: [week7-data-titanic.csv](https://raw.githubusercontent.com/hrbae/DRB_ML_Training/main/2022/week7/data/titanic.csv)


```{.py}
import numpy as np
import pandas as pd
import matplotlib.pyplot as plt
import seaborn as sns

from sklearn.neighbors import KNeighborsClassifier
from sklearn.preprocessing import MinMaxScaler

df = pd.read_csv('https://raw.githubusercontent.com/hrbae/DRB_ML_Training/main/2022/week7/data/titanic.csv')
```


------



# 4교시: 연관규칙

https://youtu.be/CajCamy3UVA

## 데이터 로드 코드

* 파일 위치: [week8-data-CBC.csv](https://raw.githubusercontent.com/hrbae/DRB_ML_Training/main/2022/week8/data/CBC.csv)


### 라이브러리 및 데이터 로드 코드

```{.py}
import numpy as np
import pandas as pd

from mlxtend.frequent_patterns import apriori
from mlxtend.frequent_patterns import association_rules

df = pd.read_csv('https://raw.githubusercontent.com/hrbae/DRB_ML_Training/main/2022/week8/data/CBC.csv')
```

------


# 7교시: 범주형 데이터를 사용한 시계열 분석

https://youtu.be/SBx3eu9EXPw

## 데이터 로드 코드

* 파일 위치: [week8-data-Amtrak.csv](https://raw.githubusercontent.com/hrbae/DRB_ML_Training/main/2022/week8/data/Amtrak.csv)


## 라이브러리 및 데이터 로드 코드

```{.py}
import numpy as np
import pandas as pd
import matplotlib.pyplot as plt
import seaborn as sns

from sklearn.preprocessing import MinMaxScaler
from sklearn.linear_model import LinearRegression

df = pd.read_csv('https://raw.githubusercontent.com/hrbae/DRB_ML_Training/main/2022/week8/data/Amtrak.csv')
```


------


# 8교시: ARIMA 시계열 분석


https://youtu.be/T4CNrWqw_ts


## 데이터 로드 코드

* 파일 위치: [week8-data-Amtrak.csv](https://raw.githubusercontent.com/hrbae/DRB_ML_Training/main/2022/week8/data/Amtrak.csv)



```{.py}
import numpy as np
import pandas as pd
import matplotlib.pyplot as plt
import seaborn as sns

from sklearn.preprocessing import MinMaxScaler

df = pd.read_csv('https://raw.githubusercontent.com/hrbae/DRB_ML_Training/main/2022/week8/data/Amtrak.csv')
```
