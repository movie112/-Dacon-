# 🏃‍♀️ Dacon : 코드 유사성 판단 AI 경진대회
두 코드 간 유사성 여부를 판단할 수 있는 AI알고리즘 개발
## Preprocessing
간단한 data cleaning     
BM25를 활용하여 유사한 code pair 생성

## Model
<p><img src="https://user-images.githubusercontent.com/56140795/195454198-725ec7cb-d5b5-4637-ae7c-17f9f1f2c0da.png" width="180" height="200"/></p>   

- ```bi-encoder``` 구조              
- SBERT에서 성능이 좋았던 ```MEAN Pooling``` Strategy 적용

## Result
- public score : 0.85885

Fold를 이용함으로써 성능향상 보임.

