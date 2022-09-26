# AIFFEL_DATATHON
 * AIFFEL에서 진행한 1차 데이터톤
 * 기간 : 2022. 03. 08 ~ 2022. 03. 11
 * 데이터셋 : [Netflix Movies and TV Shows](https://www.kaggle.com/datasets/shivamb/netflix-shows)
***
## 목차
1. [데이터톤 소개](##1.-데이터톤-소개)<br>
2. [팀 소개](##2.-팀-소개)<br>
3. [주제 소개](##3.-주제-소개)<br>
***
## 1. 데이터톤 소개
### 1차 데이터톤 취지
 * 대회에서 사용되는 데이터에 어떤 것이 있는지 알아보자.
 * 데이터를 어떻게 처리할지를 고민해보자.
 * 고민한 내용을 바탕으로 데이터를 처리하는 경험을 해보자.
### 평가표
|항목|100|
|---|---|
|EDA 및 시각화가 적절하게 이루어졌는가?|15|
|데이터 분석을 통한 인사이트가 도출이 잘 되었는가?|15|
|도출한 인사이트를 통해 설득력이 충분하였는가?|20|
|도출한 인사이트를 통해 설득력이 충분하였는가?|25|
|발표시간을 준수하였는지?|25|
|가점 : 교육생 여러분들의 평가 (참신해요, 흥미있어요, 좋아요)|-|
***
## 2. 팀 소개
* 팀명 : 넷플톤
* 팀원 및 역할
  |이름|역할|
  | :---: | :---: |
  |박성돈|수집된 자료와 코드 정리|
  |이광민|의견 정리 & 피그마 관리|
  |노경은|자료찾기 & 노션 페이지 관리|
***
## 3. 주제 소개
### _"요즘 넷플릭스 뭐 봐?”_

안부를 묻듯 이 질문은 요즘 자연스럽게 묻는 질문이 되었습니다. 코로나19 팬데믹 이후 집안에 머무는 시간이 증가하면서 가장 수혜를 받은 기업은 넷플릭스가 아닐까 생각이 듭니다. 넷플릭스는 전 세계 가입자가 2억 명에 육박하고 무서운 성장세를 보이고 있지만, 최근 디즈니 플러스, HBO 맥스, 애플 TV 등 새로운 OTT 서비스의 등장으로 입지가 위험하지 않냐는 우려의 목소리가 들리기도 합니다. 그럼에도 불구하고 ***넷플릭스가 절대 강자의 자리를 내어주지 않는 이유가 무엇일까?*** 궁금증이 생깁니다.

### _"동영상 콘텐츠 유료 이용 서비스 1위"_

오픈서베이 콘텐츠 트렌드 리포트 2019에 따르면, 넷플릭스는 주 이용 유료 동영상 서비스 분야에서 압도적인 1위를 달리고 있습니다(47.3%).<br>
![image](https://user-images.githubusercontent.com/96903792/192310539-253870f9-654b-47f4-a1c3-349dd354ecc2.png)<br>
그렇다면 사람들은 왜 넷플릭스를  주로 이용한다고 답변 하였을까요? 넷플릭스 주 이용자들은 가장 큰 이유로 ‘콘텐츠의 수가 많아서(64.1%)’, ‘여기서만 이용할 수 있는 특정 콘텐츠가 있어서(56.4%)’를 꼽았습니다.<br>
<br>
![image](https://user-images.githubusercontent.com/96903792/192310848-86b42219-2817-4730-bf81-18c17feadbca.png)<br>
[참고기사 링크](https://blog.opensurvey.co.kr/article/contents-trend-2019/)

### _"가설을 세워보자"_
본격적으로 위 설문을 바탕으로 하여 넷플릭스 컨텐츠 수와 다양성에 대해 파헤쳐보기로 했습니다.  
데이터셋은 캐글에서 제공한 ‘****Netflix Movies and TV Shows’**** 를 활용하였습니다.  
제공된 데이터 셋 안에서 넷플릭스가 인기 있는 이유를 설명하기 위해 세 가지 가설을 세우고, 그 가설에 대한 내용을 시각화하여 확인해 보겠습니다.

**1. 첫 번째 가설**

넷플릭스가 인기있는 이유는 컨텐츠의 종류가 다양하기 때문이다.

**2. 두 번째 가설**

넷플릭스가 인기있는 이유는 다양한 연령대의 컨텐츠가 존재하기 때문이다.

**3. 세 번째 가설**

넷플릭스가 인기있는 이유는 꾸준히 영상을 업데이트하기 때문이다.
