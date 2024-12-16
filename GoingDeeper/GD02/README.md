# AIFFEL Campus Online Code Peer Review Templete
- 코더 : 김영민
- 리뷰어 : 김용석


# PRT(Peer Review Template)
- [X]  **1. 주어진 문제를 해결하는 완성된 코드가 제출되었나요?**
    - CutMix와 MixUp 기법을 ResNet50 분류기에 성공적으로 적용함
    -  다양한 실험( 좌우 반전, 밝기 조절, hue조절)을 통하여 여러가지 Augmentation 기법을 적용한 결과를 체계적으로 정리
     ![image](https://github.com/user-attachments/assets/ffbdd0b4-b343-4bdd-9a2a-f263e4d8f324)

    
- [X]  **2. 전체 코드에서 가장 핵심적이거나 가장 복잡하고 이해하기 어려운 부분에 작성된 
주석 또는 doc string을 보고 해당 코드가 잘 이해되었나요?**
    - 해당 코드 블럭을 왜 핵심적이라고 생각하는지 확인
    - 해당 코드 블럭에 doc string/annotation이 달려 있는지 확인
    - 해당 코드의 기능, 존재 이유, 작동 원리 등을 기술했는지 확인
    - 주성을 통하여 실험 코드의 구조를 명시하여 코드를 한눈에 볼 수 있었다.
    - 실험 내용을 기입하여 시도한 방법들을 이해 할 수 있었음
     ![image](https://github.com/user-attachments/assets/87fa2cc5-b2cf-43fc-b62e-9d60027d7c46)
     ![image](https://github.com/user-attachments/assets/ac6a7ffe-b528-4fdc-8f4a-56e1dc38da35)

        
- [X]  **3. 에러가 난 부분을 디버깅하여 문제를 해결한 기록을 남겼거나
새로운 시도 또는 추가 실험을 수행해봤나요?**
    - 문제가 되었던 코드와 수정 된 부분을 잘 명시하였음 
     ![image](https://github.com/user-attachments/assets/8d27ab9d-a148-4d58-a5a8-ca2b5a647cfa)

        
- [X]  **4. 회고를 잘 작성했나요?**
    - 전체적인 실험에 대한 고민을 잘 작성하였으며, 현재 결과의 제한점 추가 필요 실험 등을 명시하였음.
    - 실험에 사용 된 방법등과 이유를 명시하여 합리적이 실험설계를 진행하였음
     ![image](https://github.com/user-attachments/assets/108ee376-4488-4474-a3df-d112faf45eba)
     ![image](https://github.com/user-attachments/assets/1ff4ae89-8900-4b7b-90ab-39481e35a276)

        
- [X]  **5. 코드가 간결하고 효율적인가요?**
    - 기능의 함수화를 통하여 코드의 중복을 줄이고 간결하게 코드를 작성하였
      ![image](https://github.com/user-attachments/assets/74aa97e7-9c34-45eb-9738-19b1aa081a73)
      ![image](https://github.com/user-attachments/assets/b3444fc3-d241-48af-bf2c-56a5ec6616e0)



# 회고(참고 링크 및 코드 개선)
```
코더의 회고에 작성한 것처럼 cutmix논문의 결과를 참고하면 약 150~200 에폭을 넘어야 더 좋은 결과를 나타내는 모습 확인되었습니다.
추가 실험을 통하여 실제 해당 현상이 일어나는지를 확인하고 augmentation의 효과를 확인해보면 좋을 것 같습니다.

```
