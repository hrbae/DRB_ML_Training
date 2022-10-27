# 2교시 & 3교시: SVM을 활용한 데이터 분류

https://youtu.be/FIamHFaMNJc



## 데이터 로드 코드

* 파일 위치: [week7 - data - iris.csv](https://github.com/hrbae/DRB_ML_Training/blob/main/2022/week7/data/iris.csv)

```{.py}
import pandas as pd

df = pd.read_csv('https://raw.githubusercontent.com/hrbae/DRB_ML_Training/main/2022/week7/data/iris.csv')
```



## 그리드 생성 코드

```{.py}
#주어진 데이터의 값 범위에 해당하는 격자를 생성하는 함수 정의
def make_meshgrid(x,y,h=.02):
    x_min, x_max=x.min()-1,x.max()+1 #X0에서 제일 작은 값, 큰 값
    y_min, y_max=y.min()-1,y.max()+1 #X1에서 제일 작은 값, 큰 값
    xx,yy=np.meshgrid(np.arange(x_min,x_max,h), np.arange(y_min,y_max,h))
    return xx,yy
    
    
# 그리드 생성
X0, X1 = X[:,0], X[:,1]
xx0, xx1 = make_meshgrid(X0,X1)
    
    
# 그리드 정규화
xgrid = np.c_[xx0.ravel(),xx1.ravel()]
xgridstan = scaler.transform(xgrid)
```



------



# 5교시: Naive Bayes를 활용한 분류

https://youtu.be/HDR_XZeI2as



## 데이터 로드 코드

```{.py}
import pandas as pd

df = pd.read_csv('https://raw.githubusercontent.com/hrbae/DRB_ML_Training/main/2022/week7/data/titanic.csv')
```



------



# 7교시 & 8교시: 다양한 기법의 클러스터링 적용

https://youtu.be/Wf_rvygHogg



## 한글 폰트 다운로드 및 설정 코드

```{.py}
#폰트 다운로드
!sudo apt-get install -y fonts-nanum
!sudo fc-cache -fv
!rm ~/.cache/matplotlib -rf
```

```{.py}
import matplotlib.pyplot as plt
import seaborn as sns

#한글 폰트 설정
plt.rc('font', family='NanumBarunGothic')
```





## 데이터 로드 코드

```{.py}
import pandas as pd

df = pd.read_csv('https://raw.githubusercontent.com/hrbae/DRB_ML_Training/main/2022/week7/data/public%20utilites.csv')
```

