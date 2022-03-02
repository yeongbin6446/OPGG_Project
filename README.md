# OPGG_Project(교내공모전)
1. 대회명: Hallym/OP.GG Game Big Data Hackathon
2. 참가자격: 한림대학교 재학생(학부생, 대학원생), 조별 4인까지
3. 대회내용
   - 게임대상: 리그오브레전드, 배틀그라운드 중 선택
   - 분석주제: 자유
   - 데이터 분석하여 1. 새로운 서비스 2. 게임 분석을 위한 새로운 지표 3. 새로운 아이디어 제안
## 프로젝트 소개
Riot Developer Portal 에서 API KEY를 발급 받아 게임 데이터를 입수, 가공하여 롤 MBTI를 만들었다.
### 아이디어 선정 이유
OP.GG는 라이엇이 제공하는 리그오브레전드의 데이터 분석을 통한 컨텐츠를 유저들에게 제공하는 사이트이다. 게임에 실용적인 정보 뿐 아니라 흥미에 초점을 둔 컨텐츠 또한 필요하다고 생각했다. MBTI검사와 같은 심리검사가 유행하였고, 이를 리그오브레전드 데이터에 접목하여 개인의 플레이 성향을 분석해보면 좋지 않을까 라는 생각에서 출발했다.
### 아이디어 설명
![standard](https://user-images.githubusercontent.com/96339641/156283744-b3f6bcfd-c466-452b-9ffb-7e7eccd9120c.PNG)
### 실무적 제안과 발전 방향
개개인의 성향을 설명해 놓은 페이지를 제작하여 보여준다.   
사용자가 OP.GG에서 전적을 검색하거나 멀티서치를 이용할 때 개인의 플레이 유형을 보여준다.   
플레이 유형별 최적, 최악의 궁합을 보여준다.   
유형을 평가하는 기준을 구체화하고 유형을 다양화하여 더욱 정확한 결과를 도출하도록 발전 가능하다.   
## 나의 역할
### 적극(A) VS 소극(P)
분석 대상의 게임닉네임을 이용해 게임 데이터를 불러와 대상의 킬 관여율을 계산한다. 이를 기준으로 평균값과 대조해 A인지 P인지 결정한다.   
킬관여율 = (한게임의 킬 + 어시스트) / (아군의 전체 킬) * 100   
미리 구한 그랜드마스터 200명의 평균 킬 관여율을 기준으로 삼아 성향을 결정한다.   
![aveKIR](https://user-images.githubusercontent.com/96339641/156290236-c2bc5a9f-d6f7-43dc-af57-0917521f4350.PNG)
![aveKIR2](https://user-images.githubusercontent.com/96339641/156290265-85b7fa37-a107-4b9a-b51f-b222c3649aef.PNG)

