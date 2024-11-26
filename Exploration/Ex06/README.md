# AIFFEL Campus Online Code Peer Review Templete
- 코더 : 김영민
- 리뷰어 : 이창민


# PRT(Peer Review Template)
- [O]  **1. 주어진 문제를 해결하는 완성된 코드가 제출되었나요?**
    - 문제에서 요구하는 최종 결과물이 첨부되었는지 확인
        - 중요! 해당 조건을 만족하는 부분을 캡쳐해 근거로 첨부
        - Abstractive 모델 구성을 위한 텍스트 전처리 단계가 체계적으로 진행되었다.
        - 중복 데이터 삭제, 결측값 삭제, max_len 분석 및 적절한 상수 선택, 텍스트 전처리, 테스트 데이터 분리, 정수 인코딩 등 완료
        - <img width="904" alt="스크린샷 2024-11-26 오후 5 27 38" src="https://github.com/user-attachments/assets/46942103-e190-429d-ae20-ce3c4403445a">
        - <img width="422" alt="스크린샷 2024-11-26 오후 5 27 13" src="https://github.com/user-attachments/assets/00c140da-e844-446f-8987-fbb95371eaa7">
        - <img width="447" alt="스크린샷 2024-11-26 오후 5 26 14" src="https://github.com/user-attachments/assets/b81a1725-0fc9-4669-bdb7-f6ed8bb715d2">
        - <img width="729" alt="스크린샷 2024-11-26 오후 5 26 39" src="https://github.com/user-attachments/assets/938e13c5-64fc-48f2-ab4c-ccab35776e12">
        - 이후 어텐션 모델을 사용해서 모델 훈련 완료 및 제대로 훈련되는 양상 그래프로 확인 가능
        - <img width="429" alt="1 1" src="https://github.com/user-attachments/assets/f752c0d8-c139-4fbd-99a8-75f4aa866073">
        - 추출, 추상적 요약 비교 표 완성
        - <img width="681" alt="스크린샷 2024-11-26 오후 5 37 57" src="https://github.com/user-attachments/assets/58d4115b-6e9d-42a1-8d0d-64ff148bf3c7">




    
- [O]  **2. 전체 코드에서 가장 핵심적이거나 가장 복잡하고 이해하기 어려운 부분에 작성된 
주석 또는 doc string을 보고 해당 코드가 잘 이해되었나요?**
    - 해당 코드 블럭을 왜 핵심적이라고 생각하는지 확인
    - 해당 코드 블럭에 doc string/annotation이 달려 있는지 확인
    - 해당 코드의 기능, 존재 이유, 작동 원리 등을 기술했는지 확인
    - 주석을 보고 코드 이해가 잘 되었는지 확인
        - 중요! 잘 작성되었다고 생각되는 부분을 캡쳐해 근거로 첨부
        - 전처리 코드가 꽤 복잡했는데, 주석을 잘 알아볼 수 있게 남겨놨음
        - <img width="904" alt="스크린샷 2024-11-26 오후 5 27 38" src="https://github.com/user-attachments/assets/abdd1c90-78c7-440b-9c62-abbf9a81a499">

        
- [O]  **3. 에러가 난 부분을 디버깅하여 문제를 해결한 기록을 남겼거나
새로운 시도 또는 추가 실험을 수행해봤나요?**
    - 문제 원인 및 해결 과정을 잘 기록하였는지 확인
    - 프로젝트 평가 기준에 더해 추가적으로 수행한 나만의 시도, 
    실험이 기록되어 있는지 확인
        - 중요! 잘 작성되었다고 생각되는 부분을 캡쳐해 근거로 첨부
        - 우선 EarlyStopping을 사용하지 않은 학습을 하는 새로운 시도 발견
        - ![ex0501](https://github.com/user-attachments/assets/03e6195e-668d-424b-a0a7-59e6a5c36e65)
        - 리뷰어도 생겼던 같은 문제인 인풋이 작을 때 ratio가 작동하지 않는 문제 캐치, 해결
        - <img width="704" alt="스크린샷 2024-11-26 오후 5 34 49" src="https://github.com/user-attachments/assets/1635377c-6791-42fb-9b4c-44f14e204581">


        
- [O]  **4. 회고를 잘 작성했나요?**
    - 주어진 문제를 해결하는 완성된 코드 내지 프로젝트 결과물에 대해
    배운점과 아쉬운점, 느낀점 등이 기록되어 있는지 확인
    - 전체 코드 실행 플로우를 그래프로 그려서 이해를 돕고 있는지 확인
        - 중요! 잘 작성되었다고 생각되는 부분을 캡쳐해 근거로 첨부
        - 회고칸에 잘 작성된 모습을 볼 수 있음
        - <img width="676" alt="스크린샷 2024-11-26 오후 5 36 13" src="https://github.com/user-attachments/assets/dd2c60b5-abb2-49d8-b01a-57fd11740a7f">

        
- [O]  **5. 코드가 간결하고 효율적인가요?**
    - 파이썬 스타일 가이드 (PEP8) 를 준수하였는지 확인
    - 코드 중복을 최소화하고 범용적으로 사용할 수 있도록 함수화/모듈화했는지 확인
        - 중요! 잘 작성되었다고 생각되는 부분을 캡쳐해 근거로 첨부
        - 재사용할 수 있도록 모듈화
        - <img width="695" alt="스크린샷 2024-11-26 오후 5 39 18" src="https://github.com/user-attachments/assets/d81837a8-d3db-4b71-848a-76ad73fee88b">



# 회고(참고 링크 및 코드 개선)
```
전체적으로 수업 내용을 잘 따라가며 정석적으로 결과까지 가는 흐름이 이어졌다.
그 과정에서 해결되지 않는 부분들에 대한 흔적이 남겨져있고 뒤에 추가실험에서 해당 부분을 해결하는 방법이 잘 작성되어있다.

특히 다른 부분보다 추가 실험해볼 것 칸에 있는 부분에 흥미가 많이 갔다.
오늘 내에 해결하지 못했거나 추가적으로 분석하고 적용할 수 있는 부분을 놓치지 않았다는 점이 대단하다고 생각했다.
<img width="689" alt="스크린샷 2024-11-26 오후 5 41 51" src="https://github.com/user-attachments/assets/e079f1c3-7836-440d-990e-f74544706363">
```
