## 🎥 팝콘Angle



### 📋 프로젝트 정보

* 팀명 : 자처한 준기
* 팀장 : 김준기
* 팀원 : 길민규, 김재호, 정다솜, 차종욱
* 프로젝트 : 영화 추천 사이트
* 기간 : 2020.08.31 ~ 2020.10.9



<br />

### 💡 Local 실행 방법

git clone 후 해야하는 작업

#### FrontEnd

```sh
$ npm install
$ npm run serve
```

#### BackEnd

```sh
$ python -m venv venv
$ source venv/Scripts/activate
$ pip install -r requirements.txt
$ python manage.py migrate	
$ python manage.py createsuperuser
$ python manage.py runserver
```




<br />


### 💡 팀원 정보 및 역할 분담

| 팀원   | 역할 | 비고                             |
| ------ | ---- | -------------------------------- |
| 김준기 | 팀장 | FE / BE, AWS. Git관리            |
| 길민규 | 팀원 | FE / BE, Git관리, 저녁 메뉴 선정 |
| 김재호 | 팀원 | FE / BE, AWS. Jira관리           |
| 정다솜 | 팀원 | FE / BE, Jira관리, 데이터 관리 |
| 차종욱 | 팀원 | FE / BE, DB, 데이터 크롤링       |

<br />

### 💡 목표 서비스 구현 및 실제 구현 정도

#### 목표 서비스

* 영화 빅데이터를 활용한 추천 서비스 구성

* 커뮤니티 서비스 구성

* 데이터 크롤링 및 Open API 활용

* HTML, CSS, JavaScript, Vue.js, Django, REST API, MariaDB 등을 활용한 실제 서비스 설계

* Python, Pandas, Numpy 등을 활용한 빅데이터 정제 및 추천 알고리즘 구현

* AWS, EC2를 활용한 서비스 배포 및 관리

  

#### 실제 구현도

* Vue.js 와 Django REST Framework를 활용한 서비스 설계

* Naver 데이터 크롤링 및 KMDB Open API 활용해 빅데이터 만듬

* 추천 알고리즘 구현

  - 날씨 API를 활용한 날씨별 영화 장르 추천
  - 최근 본 영화 및 평점 기반으로 감독별/장르별/배우별/키워드별 영화 추천
  - 아이템 기반 협업 필터링, 사용자 기반 협업 필터링을 활용한 영화 추천

* HTML, CSS, JS을 활용한 UI/UX



#### 차별점

* SQLite3 대신 MariaDB를 활용해 DB를 구성함

* 아이템 기반 협업 필터링, 사용자 기반 협업 필터링 등 여러 가지의 Pandas기반의 알고리즘 구현 시도

* 기존 영화 데이터의 부족한 정보로 인해 데이터 크롤링 및 정제를 통해 영화에 대한 다양한 정보를 담아냄


#### 아쉬운점

* 기존에 계획했던 MongoDB를 활용해보지 못한 점
( 멘토링을 통해 익숙한 DB를 사용하는 것을 추천 받음)

* 7주 간의 기간 중 추석연휴 및 취업 준비로 인한 프로젝트 집중에 대한 아쉬움

  

<br />


### 💡 개발 환경

##### Frontend (Vue.js)

- axios : 0.20.0

- bootstrap : 4.5.2

- bootstrap-vue : 2.17.3

- vue : 2.6.12

- vue-cookies : 1.7.4

- vue-router : 3.2.0

  


##### Backend (Django REST API 서버)

- Django : 2.2.7

- Django REST framework : 3.10.3

- Python : 3.6.8

- pandas : 0.25.3

- numpy : 1.17.3

  

##### 서비스 배포 환경

- AWS



<br />

### 💡 기능

#### Accounts

- 유저 프로필 화면



#### Movie

* 추천 알고리즘을 통해 기본적인 영화 추천 가능

* 원하는 기준으로 영화 목록을 볼 수 있음



#### Community

* 회원은 평점, 리뷰 등록 가능

  

