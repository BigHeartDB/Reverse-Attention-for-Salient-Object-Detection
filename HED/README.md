Holistically-Nested Edge Detection
----------------------------------

#### Abstract
```
 Our *new Edge detection algorithm* addresses two issues.
1. Holistic image training and predictions.
2. Multi-scale and multi-level feature learning.


```

### 1. Introduction
```
 - Holistic <- FCN의 image-to-image classification에서 영감을 받음.
 
- Deeply-supervised nets에서 영감을 받아 nested multi-scale feature learning을 고안하였다.
[Nested : side-output1을 refine하여 2를 만들고, 또 side-output2를 refine하여 3를 만드는 식으로
 점진적으로 발전시켜 나가기 때문에 '엮여 있다'는 의미로 nested라고 이름을 지은듯하다.

```

### 2. Holistically-Nested Edge Detection
```
1) Formulation detail : cnn방식 기반부터 논의 시작. 특히 multi-scale, level feature learning에 관하여.

FCN을 보고 end-to-end를 고안하였으나 VGG nets를 사용.

deep supervision과 side outputs의 부재로 성능이 충분치 않음. (FCN사용시 F=.745)

```

- deep supervision이란 무엇인가? -> more transparent feature를 학습하도록 guiding.
- 

#### 2.1. Existing multi-scale and multi-level NN
```

```
