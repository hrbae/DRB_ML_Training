# 3교시: Perceptron

https://youtu.be/pDPa-Gfxiqk



# 4교시: MLP

https://youtu.be/YCHgn4AOdls



## 시드 고정 및 데이터 로드 코드

* 시드 고정

```{.py}
# 실행마다 동일한 결과를 얻기 위해 케라스에 랜덤 시드를 사용하고 텐서플로 연산을 고정
import tensorflow as tf

tf.keras.utils.set_random_seed(42)
tf.config.experimental.enable_op_determinism()
```

* 데이터 로드

```{.py}
from tensorflow import keras
(X_train, y_train), (X_test, y_test) = keras.datasets.fashion_mnist.load_data()
```



## 모델 컴파일 코드

```{.py}
model.compile(loss = 'sparse_categorical_crossentropy', metrics = 'accuracy')  #다중 분류 시 손실함수
```



------



# 6교시: 경사하강법

https://youtu.be/sKarrljsLmk





# 8교시: 오버피팅(과적합)

https://youtu.be/pmf5FUx8rng



## 시드 고정 및 데이터 로드 코드

* 시드 고정

```{.py}
# 실행마다 동일한 결과를 얻기 위해 케라스에 랜덤 시드를 사용하고 텐서플로 연산을 고정
import tensorflow as tf

tf.keras.utils.set_random_seed(42)
tf.config.experimental.enable_op_determinism()
```

* 데이터 로드

```{.py}
from tensorflow import keras
(X_train, y_train), (X_test, y_test) = keras.datasets.fashion_mnist.load_data()
```



