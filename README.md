# G18_Action_Stickers

# Project: 모델 바꿔보기

## STEP 1 : simplebaseline 모델 완성하기
- simplebaseline.py 프로그램 완성

## STEP 2 : simplebaseline 모델로 변경하여 훈련하기
- train_sb.py 218라인의 모델 선언 부분을 simplebaseline 모델로 변경하였으나, 학습이 잘 되지 않았음

## STEP 3 : 두 모델의 비교
- 실습에서 다룬 StackedHourglass Network와 Simplebaseline 모델을 둘 다 동일한 Epoch 수만큼 학습하여 그 결과를 비교해 봅니다.

## Pose Estimation 결과 시각화 (정성적 비교)

## 학습 진행 경과

### - 첫번째 시도에서 StackedHourglass Network 모델은 Validation Loss가 15 Epoch에서 1.5659 까지 낮아졌다. 

![learning_result1](https://user-images.githubusercontent.com/39249809/102385787-9c8c6380-4011-11eb-9ced-b5c29bf09803.png)

### - 두번째 시도에서는 위의 학습 결과를 불러와서 Validation Loss가 2 Epoch에서 1.2269 까지 낮아졌다. 

![learning_result](https://user-images.githubusercontent.com/39249809/102421670-5272a480-4048-11eb-9db2-a2133252677f.png)


## 결과 시각화

### Test 1 결과 이미지

![test0_p](https://user-images.githubusercontent.com/39249809/102420925-9795d700-4046-11eb-84e9-52ab942372bf.jpg)
![test0_s](https://user-images.githubusercontent.com/39249809/102420934-9b295e00-4046-11eb-8cc7-c867961d8e02.jpg)

### Test 2 결과 이미지

![test1_p](https://user-images.githubusercontent.com/39249809/102420939-9c5a8b00-4046-11eb-8667-08a55b37640c.jpg)
![test1_s](https://user-images.githubusercontent.com/39249809/102420940-9d8bb800-4046-11eb-87a3-3db15e6f28d5.jpg)

### Test 3 결과 이미지

![test2_p](https://user-images.githubusercontent.com/39249809/102420944-9e244e80-4046-11eb-8729-75778740e17c.jpg)
![test2_s](https://user-images.githubusercontent.com/39249809/102420945-9ebce500-4046-11eb-9f8d-30adc5d9d5f8.jpg)

### Test 4 결과 이미지

![test3_p](https://user-images.githubusercontent.com/39249809/102420948-9fee1200-4046-11eb-9685-2483aa0af115.jpg)
![test3_s](https://user-images.githubusercontent.com/39249809/102420950-a086a880-4046-11eb-9efb-eff39415c582.jpg)

### Test 5 결과 이미지

![test4_p](https://user-images.githubusercontent.com/39249809/102420951-a11f3f00-4046-11eb-8662-24bb29827cd6.jpg)
![test4_s](https://user-images.githubusercontent.com/39249809/102420953-a1b7d580-4046-11eb-99de-08cc87bded68.jpg)

### Test 6 결과 이미지

![test5_p](https://user-images.githubusercontent.com/39249809/102420954-a2506c00-4046-11eb-9ed1-e29bd56ff9b2.jpg)
![test5_s](https://user-images.githubusercontent.com/39249809/102420956-a2e90280-4046-11eb-9497-1f79f0d4cd9c.jpg)

### Test 7 결과 이미지

![test6_p](https://user-images.githubusercontent.com/39249809/102420958-a41a2f80-4046-11eb-8107-deee33ce5502.jpg)
![test6_s](https://user-images.githubusercontent.com/39249809/102420960-a4b2c600-4046-11eb-8d5f-4bcd6f802035.jpg)


### Test 8 결과 이미지

![test7_p](https://user-images.githubusercontent.com/39249809/102420964-a54b5c80-4046-11eb-9ea0-0cd84bc0c08e.jpg)
![test7_s](https://user-images.githubusercontent.com/39249809/102420969-a67c8980-4046-11eb-8c4f-7f1e9c48d0e7.jpg)


### Test 9 결과 이미지

![test8_p](https://user-images.githubusercontent.com/39249809/102420970-a67c8980-4046-11eb-992d-3fdbfadfe3f4.jpg)
![test8_s](https://user-images.githubusercontent.com/39249809/102420973-a7152000-4046-11eb-986d-3a73111237e2.jpg)


