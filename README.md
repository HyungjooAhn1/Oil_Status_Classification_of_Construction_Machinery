![20221213_235022](https://user-images.githubusercontent.com/101160593/207366058-5b95d8f3-3f5c-49b0-a00d-c80ba5310cc6.png)

## 1. 대회
**건설기계 오일 상태 분류 AI 경진대회** <br>

## 2. 주제
건설장비에서 작동오일의 상태를 실시간으로 모니터링하기 위한 오일 상태 판단 모델 개발 (정상, 이상의 이진분류)

## 3. 팀 소개
- T1 
  - [나해란](https://github.com/Nahaeran)
  - [안형주](https://github.com/HyungjooAhn1)
  - [장영진](https://github.com/yjjangg)
  - [장효정](https://github.com/hfairyz)
<br>

## 4. 모델링
### 1) Teacher Model
![3](https://user-images.githubusercontent.com/101160593/208299469-d5a8b14e-d778-44d2-b560-aaf28b82bbf0.png)
<br>

### 2) Student Model
#### Step 1
![1](https://user-images.githubusercontent.com/101160593/208299149-9f842ce8-8513-48f5-984e-3e8e499f6bf1.png)

#### Step 2
![2](https://user-images.githubusercontent.com/101160593/208299319-9fe00a7d-5ef6-4365-be61-a73084a63c1e.png)

## 5. 제출 결과
![1672362649105982](https://user-images.githubusercontent.com/101160593/210036302-71cd3f62-6de0-4778-b92d-0b8da4c89bf8.png)


## 6. 의의
1. Tried many Experiments to handle Imbalanced Data in Regression

2. To prevent information loss, we made our own solution using all data

3. We found important features that influences Abnormal status in Diagnostic Environment

4. Our Model and Strategy can contribute to Construction Machinery Intelligence

## 7. 한계점

1. Not enough Domain Knowledge -> Preprocess Missing Value

2. Focused more on Regression, better classification model could make better score

3. Didn't try Deep Learning Model
