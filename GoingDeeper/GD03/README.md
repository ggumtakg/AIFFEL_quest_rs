# AIFFEL Campus Online Code Peer Review Templete
- 코더 : 김영민
- 리뷰어 : 김준석


# PRT(Peer Review Template)
- [O]  **1. 주어진 문제를 해결하는 완성된 코드가 제출되었나요?**
    - 문제에서 요구하는 최종 결과물이 첨부되었는지 확인
        - 중요! 해당 조건을 만족하는 부분을 캡쳐해 근거로 첨부  
    1. CAM을 얻기위한 기본모델의 구성과 학습이 잘 진행되었습니다.  
    <img width="585" alt="image" src="https://github.com/user-attachments/assets/03f44370-b9a4-474d-a20b-b091bbe0311d" /><br>
    2. 분류 근거를 설명 가능한 CAM을 얻었습니다.  
    <img width="295" alt="image" src="https://github.com/user-attachments/assets/00d58df6-ff7e-4519-80e1-5f064144b23c" /><br>
    <img width="557" alt="image" src="https://github.com/user-attachments/assets/ea864f36-7abb-4e48-b64d-5e0894c95672" /><br>
    3. 인식결과의 시각화 및 성능 분석을 적절히 수행하였습니다.  
    <img width="372" alt="image" src="https://github.com/user-attachments/assets/10548f71-511e-4bfd-ab76-df6af884abcd" /><br>
 
- [O]  **2. 전체 코드에서 가장 핵심적이거나 가장 복잡하고 이해하기 어려운 부분에 작성된 
주석 또는 doc string을 보고 해당 코드가 잘 이해되었나요?**
    - 해당 코드 블럭을 왜 핵심적이라고 생각하는지 확인
    - 해당 코드 블럭에 doc string/annotation이 달려 있는지 확인
    - 해당 코드의 기능, 존재 이유, 작동 원리 등을 기술했는지 확인
    - 주석을 보고 코드 이해가 잘 되었는지 확인
        - 중요! 잘 작성되었다고 생각되는 부분을 캡쳐해 근거로 첨부  
      -> 직접 모델을 구성하고 새롭게 cam과 grad cam을 출력해 본점이 흥미로웠습니다.  
      <img width="590" alt="image" src="https://github.com/user-attachments/assets/7a9b7393-a751-4fd8-99f4-63964560947f" /><br>
      <img width="556" alt="image" src="https://github.com/user-attachments/assets/613cce98-e8ba-42ef-8ad6-61f4ec1567a1" /><br>
      <img width="359" alt="image" src="https://github.com/user-attachments/assets/0478cc16-689b-4f18-8e9f-1e7aa733fcda" /><br>
      -> 추가실험으로 노이즈를 추가하여 cam, grad cam을 비교실험 하신것 또한 매우 흥미롭고 좋았습니다.
      <img width="580" alt="image" src="https://github.com/user-attachments/assets/e14777f5-394b-4128-9ebc-302d4cede946" /><br>
      <img width="258" alt="image" src="https://github.com/user-attachments/assets/390df3e5-8b1b-4bd7-850f-27296bb1b690" /><br>
      <img width="551" alt="image" src="https://github.com/user-attachments/assets/6dff9b0e-92b8-406c-8a51-d75bf6627637" /><br>
      
        
- [O]  **3. 에러가 난 부분을 디버깅하여 문제를 해결한 기록을 남겼거나
새로운 시도 또는 추가 실험을 수행해봤나요?**
    - 문제 원인 및 해결 과정을 잘 기록하였는지 확인
    - 프로젝트 평가 기준에 더해 추가적으로 수행한 나만의 시도, 
    실험이 기록되어 있는지 확인
        - 중요! 잘 작성되었다고 생각되는 부분을 캡쳐해 근거로 첨부  
     <img width="560" alt="image" src="https://github.com/user-attachments/assets/57e25288-de0e-4a11-861c-25bfe45d826d" /><br>

   
- [O]  **4. 회고를 잘 작성했나요?**
    - 주어진 문제를 해결하는 완성된 코드 내지 프로젝트 결과물에 대해
    배운점과 아쉬운점, 느낀점 등이 기록되어 있는지 확인
    - 전체 코드 실행 플로우를 그래프로 그려서 이해를 돕고 있는지 확인
        - 중요! 잘 작성되었다고 생각되는 부분을 캡쳐해 근거로 첨부  
        -> 총 3번의 실험에 대해, 각각의 회고를 잘 남겨주셨습니다.
     <img width="588" alt="image" src="https://github.com/user-attachments/assets/c5859633-58d1-4420-8300-c1aef2a6e3dc" /><br>
     <img width="579" alt="image" src="https://github.com/user-attachments/assets/23e0f385-b7e6-4e91-82c4-df96994e1ce2" /><br>
     <img width="571" alt="image" src="https://github.com/user-attachments/assets/1844daa2-5d7f-41a0-b398-e09c70866f88" /><br>
          
- [O]  **5. 코드가 간결하고 효율적인가요?**
    - 파이썬 스타일 가이드 (PEP8) 를 준수하였는지 확인
    - 코드 중복을 최소화하고 범용적으로 사용할 수 있도록 함수화/모듈화했는지 확인
        - 중요! 잘 작성되었다고 생각되는 부분을 캡쳐해 근거로 첨부  
        -> 간결하고 효율적으로 잘 작성해주셨습니다.
      <img width="594" alt="image" src="https://github.com/user-attachments/assets/9d6c72b0-6944-4440-8122-1d1dd53455b9" /><br>


# 회고(참고 링크 및 코드 개선)
```
다양한 추가실험들을 많이 진행해주셨는데 덕분에 저도 차근차근 읽어가며 많이 공부해갑니다ㅎㅎ!
고생많으셨어요~!
```
