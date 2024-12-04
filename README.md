
# "AI 기반 두부 결함 검출 시스템"
풀무원에서 제공된 두부 이미지 데이터를 통해 두부의 양불을 판정하는 CV프로젝트로, 
두부의 양불을 판정한 후 이를 관리자가 감독하는 대시보드까지 개발을 진행하였습니다.

<div align=center> <img width= 300 src="https://github.com/user-attachments/assets/d2d9cab8-41ff-4630-8a91-b740acc295a6">  </div>

## 👥 Contributors

|[안재현](https://github.com/Jaehyeonee)|양지원|곽지원|한수민|
|:-------:|:---------:|:----------:|:--------:|
|AI모델 개발 및 배포 <br> Cloud Architecture 설계| AI개발 및 발표 |AWS cost calculating, AI|Streamlit 대시보드 개발|


###### Development period
```- November, 2024 (11/1 ~ 11/30)```

## 🔍 Who is our Customer
***** ****
<img width="955" alt="스크린샷 2024-12-04 오후 4 53 04" src="https://github.com/user-attachments/assets/b7713604-22d6-43e4-8792-6cc18f97c1fa">

## 💡 Method 
***** ****
<img width="955" alt="스크린샷 2024-12-04 오후 4 53 44" src="https://github.com/user-attachments/assets/29dea827-e1a6-4862-9b9a-b7c33211c4db">

## ⚙️ Model- google/vit-large-patch16-224
현재 이미지 분류에서 SOTA성능을 내고 있는 Vit모델을 선정하고, 이미지 형태와 모델의 크기를 고려해 ```large-patch16-224``` 를 최종적으로 선정하여 진행
<img width="955" alt="스크린샷 2024-12-04 오후 4 57 09" src="https://github.com/user-attachments/assets/e70d8599-9a5d-4744-9fa0-ac23945919a9">

## 🔗 Model evaluation:  **```최종적으로 98.18% 정확도를 달성```**

<img width="955" alt="스크린샷 2024-12-04 오후 4 57 28" src="https://github.com/user-attachments/assets/1fc6dfe9-d1d6-41db-9d86-2caa5a8cfdeb">

## 🧊 Model 고려사항
**1. 목적에 비해 모델이 오버스팩이 아닌가**
     <img width="943" alt="스크린샷 2024-12-04 오후 5 02 12" src="https://github.com/user-attachments/assets/e4f6001f-b426-4955-a38d-ac22e95e163f">
     <img width="943" alt="스크린샷 2024-12-04 오후 5 02 31" src="https://github.com/user-attachments/assets/0ac6cd35-8ad7-407c-aa5f-0ace14d6bc48">

**2. 모델의 비용이 현실적인가**

실제 공장에서 본 모델을 사용한다고 가정했을 때 풀무원의 10개의 공장에서 ```각 공장 당 월 10만2천원의 비용``` 이 필요함을 계산하여 충분히 현실적인 솔루션임을 입증했습니다.
    <img width="953" alt="스크린샷 2024-12-04 오후 5 03 02" src="https://github.com/user-attachments/assets/560a9074-8d01-4def-9f5c-e0597186d945">
    
## 📊 관리자 대시보드 설계
<img width="908" alt="스크린샷 2024-12-04 오후 10 58 06" src="https://github.com/user-attachments/assets/8c0fcd35-04de-42f6-a5da-9123e2003fed">
<img width="908" alt="스크린샷 2024-12-04 오후 10 58 14" src="https://github.com/user-attachments/assets/a6d95907-9524-45c8-956d-736a4630770f">

## 🔗 System Architecture
<img width="955" alt="스크린샷 2024-12-04 오후 4 59 13" src="https://github.com/user-attachments/assets/c5b1e8f1-e15e-49ab-83f6-4a2ac06cdb87">

