![20221213_235022](https://user-images.githubusercontent.com/101160593/207366058-5b95d8f3-3f5c-49b0-a00d-c80ba5310cc6.png)

## Topic
**건설기계 오일 상태 분류 AI 경진대회** <br>

## Objective
건설장비에서 작동오일의 상태를 실시간으로 모니터링하기 위한 오일 상태 판단 모델 개발 (정상, 이상의 이진분류)

## Team
T1 ([나해란](https://github.com/Nahaeran), 
[안형주](https://github.com/HyungjooAhn1),
[장영진](https://github.com/yjjangg),
[장효정](https://github.com/hfairyz))

## Modeling
### Teacher Model


### Student Model Architecture
#### Step 1
![1](https://user-images.githubusercontent.com/101160593/208299149-9f842ce8-8513-48f5-984e-3e8e499f6bf1.png)

#### Step 2
![2](https://user-images.githubusercontent.com/101160593/208299319-9fe00a7d-5ef6-4365-be61-a73084a63c1e.png)

## Submission Result
**26등** (총 517팀)

## Significance
1. Tried many Experiments to handle Imbalanced Data in Regression

2. To prevent information loss, we made our own solution using all data

3. We found important features that influences Abnormal status in Diagnostic Environment

4. Our Model and Strategy can contribute to Construction Machinery Intelligence

## Limitations

1. Not enough Domain Knowledge -> Preprocess Missing Value

2. Focused more on Regression, better classification model could make better score

3. Didn't try Deep Learning Model
