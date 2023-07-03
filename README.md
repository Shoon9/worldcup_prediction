# worldcup_prediction

4년마다 계최되는 전 세계인의 축제 월드컵은 각종 언론사가 뉴스, 신문 기사를 통해 승부 예측 및 우승국가를 예측 합니다. 
2022년 카타르 월드컵이 개최된 후 언론과 매체는 우승국가 예측을 하기 시작했고 이에 따라 기사를 통해 월드컵 참가국 중 어느 나라가 우승할지 예측하기 위해 프로젝트를 진행하였습니다.
 
각 종 뉴스, 신문 기사에서 강력한 우승 후보로 생각하는 나라와 관련된 키워드의 비중이 높게 나타날 것이라고 예상했습니다. 
또한 실시간 뉴스를 수집하는 기간을 조별예선 전부터 조별예선 최종전까지 설정해뒀기 때문에 시간이 지날수록 더욱 정확한 우승후보 예측을 할 것이라고 예상했습니다.
 
> 연구 과정 및 분석 방식
 
> 1) 기간 분류
  - 조별예선 전
  - 조별예선 1차전 이 후
  - 조별예선 2차전 이 후
  - 조별예선 3차전 이 후
  - 조별예선 4차전 이 후
  
> 2) 네이버에서 “20OO년 월드컵 우승후보” 검색
 
> 3) 기간별 해당 페이지 비정형 데이터 추출
 
> 4) 추출된 키워드로 워드 클라우드 시각화 및 연관어 분석
 - 네이버에서 데이터를 추출할 때 해당 언론사 이름과 기자이름 등 불필요한 데이터는 전처리 과정을 통해 제거.
