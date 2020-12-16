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

- StackedHourglass Network 모델은 Validation Loss가 15 Epoch에서 ***1.5659***까지 낮아졌다. 

![learning_result1](https://user-images.githubusercontent.com/39249809/102385787-9c8c6380-4011-11eb-9ced-b5c29bf09803.png)


## 결과 시각화

### Test 1 결과 이미지

![test_image_p](https://user-images.githubusercontent.com/39249809/102384233-d0ff2000-400f-11eb-82ad-6d960c9f8591.jpg)
![test_image_s](https://user-images.githubusercontent.com/39249809/102384239-d197b680-400f-11eb-85d2-9e3da316b89f.jpg)

### Test 2 결과 이미지

![test1_p](https://user-images.githubusercontent.com/39249809/102384169-c2b10400-400f-11eb-99e0-335124407e54.jpg)
![test1_s](https://user-images.githubusercontent.com/39249809/102384176-c5135e00-400f-11eb-8c49-49caa7911dfb.jpg)

### Test 3 결과 이미지

![test2_p](https://user-images.githubusercontent.com/39249809/102384182-c6448b00-400f-11eb-8250-3e99197731cd.jpg)
![test2_s](https://user-images.githubusercontent.com/39249809/102384192-c775b800-400f-11eb-9297-1a1f1cdecace.jpg)

### Test 4 결과 이미지

![test3_p](https://user-images.githubusercontent.com/39249809/102384195-c93f7b80-400f-11eb-8c42-500a14dbdfa7.jpg)
![test3_s](https://user-images.githubusercontent.com/39249809/102384197-ca70a880-400f-11eb-8890-3d62019e7668.jpg)

### Test 5 결과 이미지

![test4_p](https://user-images.githubusercontent.com/39249809/102384202-cb093f00-400f-11eb-969c-6236854619e2.jpg)
![test4_s](https://user-images.githubusercontent.com/39249809/102384209-cc3a6c00-400f-11eb-91b1-8f7f0a444b63.jpg)

### Test 6 결과 이미지

![test5_p](https://user-images.githubusercontent.com/39249809/102384213-ccd30280-400f-11eb-86ef-809814ca0bd6.jpg)
![test5_s](https://user-images.githubusercontent.com/39249809/102384218-ce042f80-400f-11eb-889f-ea318f1655dc.jpg)

### Test 7 결과 이미지

![test6_p](https://user-images.githubusercontent.com/39249809/102384224-ce9cc600-400f-11eb-9208-5a77d0a8167e.jpg)
![test6_s](https://user-images.githubusercontent.com/39249809/102384228-cfcdf300-400f-11eb-8c28-bccfcb4fcd44.jpg)


