# Pre-AIFFELthon
### 에이드올 인도보행 가능 영역
인도보행 가능 영역에 사용한 fastscnn과 bisenet 학습 코드

---
### 실행 환경
주피터 노트북  
python3  
conda

---
### 사용한 데이터셋
- cityscapes  
- Surface-Indobohaeng-Selected  
- Surface-Indobohaeng-Grayscaled

---
### 파일 간단 설명
**Fastscnn**
  - cityscapes > fastscnn 사전학습

**BisenetV2**
  - cityscapes > bisenetv2 사전학습  
  - indobohaeng > bisenetv2 사전학습  
  - indobohaeng > bisenetv2 > 4클래스 파인튜닝
 
**help code**
  - 소소하게 도움되는 코드
