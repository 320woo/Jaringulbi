![image](https://user-images.githubusercontent.com/26705587/127585241-6d48cb73-6b61-479b-8404-4435ad87a879.png)

# 🐟자린굴비🐟

> 자린굴비는 쉽고 직관적인 가계부 기능을 바탕으로, 사용자간의 소통 및 챌린지 기능을 제공하는 자산관리 서비스입니다.
> 자린굴비는 MZ세대의 새로운 재테크 문화를 만들어 갑니다.



## 😎대전없는대전팀

|   Name   |                            왕영문                            |                            이산하                            |                            임현우                            |                            하태린                            |
| :------: | :----------------------------------------------------------: | :----------------------------------------------------------: | :----------------------------------------------------------: | :----------------------------------------------------------: |
| Profile  | <img width="200" src="https://user-images.githubusercontent.com/26705587/127587609-21e853bb-f47a-4989-af09-c0e0a9107d33.png"> | <img width="200" src="https://user-images.githubusercontent.com/26705587/127587653-eace5871-dda2-46c7-a75b-1faaf7e5be20.png"> | <img width="200" src="https://user-images.githubusercontent.com/26705587/127587569-fd28267a-99ee-4228-98f3-578193ac8a3a.png"> | <img width="200" src="https://user-images.githubusercontent.com/26705587/127587865-a754c895-67f4-4654-82e0-13c49820512e.png"> |
| Position |                Project leader &<br />Backend                 |                Frontend &<br />UX/UI, Design                 |                    Frontend &<br /> UI/UX                    |                    Backend & <br />DevOps                    |
|  GitHub  |            [@wym6764](https://github.com/wym6764)            |           [@sana0803](https://github.com/sana0803)           |         [@320woo](https://github.com/320woo)         |           [@hataerin](https://github.com/hataerin)           |

#### 👉[대전없는 대전팀의 협업방법 보러가기]()👈





# 🎮 기술 스택

### 💻Back-End

### ✨Front-End





# ⚙️ Install and Usage

## Font-end

1. 자린굴비 프론트 이미지 받아오기

   ```shell
   $ docker pull hotoron/jaringulbi-vue-dockerize
   ```

2. 자린굴비 프론트 도커 실행하기

   ```shell
   $ docker run -d -p 80:80 --rm --name jaringulbi-vue hotoron/jaringulbi-vue-dockerize
   ```

   

## Back-end

1. 자린굴비 백엔드 이미지 받아오기

   ``` shell
   $ docker pull hotoron/jaringulbi-spring-dockerize
   ```

2. 자린굴비 백엔드 도커 실행하기

   ``` shell
   $ docker run -d -p 8399:8399 --rm --name jaringulbi-spring hotoron/jaringulbi-spring-dockerize
   ```



## Database

1. mysql 이미지 받아오기

   ``` shell
   $ docker pull mysql
   ```

2. 자린굴비 DB 도커 실행하기

   ```shell
   $ docker run -d -p 3306:3306 -e MYSQL_ROOT_PASSWORD=1234 --name jaringulbi-mysql mysql
   ```

3. MySQL 접속해서 `b303.sql` 실행하기 (첨부파일 참조)

4. CSV파일로 더미데이터 집어넣기 (첨부파일 참조)



# 📚[WIKI](https://lab.ssafy.com/s05-webmobile2-sub2/S05P12B303/-/wikis/home)



 

## 📆Daily Scrum & Wrap-up

| 회의             | 월                                      | 화                                                           | 수                                                           | 목                                                           | 금                                      | 회고             |
| ---------------- | :-------------------------------------- | ------------------------------------------------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ | --------------------------------------- | :--------------- |
| [🧐Sprint 회의]() | **26**<br>🌞Scrum <br>🌛Wrap-up           | **27**<br/>[🌞Scrum](https://lab.ssafy.com/s05-webmobile2-sub2/S05P12B303/-/wikis/09.-Daily-Scrum#anchor-20210727) <br/>[🌛Wrap-up](https://lab.ssafy.com/s05-webmobile2-sub2/S05P12B303/-/wikis/10.-Daily-Warp-up#anchor-20210727) | **28**<br/>[🌞Scrum](https://lab.ssafy.com/s05-webmobile2-sub2/S05P12B303/-/wikis/09.-Daily-Scrum#anchor-20210728) <br/>[🌛Wrap-up](https://lab.ssafy.com/s05-webmobile2-sub2/S05P12B303/-/wikis/10.-Daily-Warp-up#anchor-20210728) | **29**<br/>[🌞Scrum](https://lab.ssafy.com/s05-webmobile2-sub2/S05P12B303/-/wikis/09.-Daily-Scrum#anchor-20210729) <br/>[🌛Wrap-up](https://lab.ssafy.com/s05-webmobile2-sub2/S05P12B303/-/wikis/10.-Daily-Warp-up#anchor-20210729) | **30**<br/>[🌞Scrum]() <br/>[🌛Wrap-up]() | [🤔Sprint 회고]() |
| [🧐Sprint 회의]() | **2**<br/>[🌞Scrum]() <br/>[🌛Wrap-up]()  | **3**<br/>[🌞Scrum]() <br/>[🌛Wrap-up]()                       | **4**<br/>[🌞Scrum]() <br/>[🌛Wrap-up]()                       | **5**<br/>[🌞Scrum]() <br/>[🌛Wrap-up]()                       | **6**<br/>[🌞Scrum]() <br/>[🌛Wrap-up]()  | [🤔Sprint 회고]() |
| [🧐Sprint 회의]() | **9**<br/>[🌞Scrum]() <br/>[🌛Wrap-up]()  | **10**<br/>[🌞Scrum]() <br/>[🌛Wrap-up]()                      | **11**<br/>[🌞Scrum]() <br/>[🌛Wrap-up]()                      | **12**<br/>[🌞Scrum]() <br/>[🌛Wrap-up]()                      | **13**<br/>[🌞Scrum]() <br/>[🌛Wrap-up]() | [🤔Sprint 회고]() |
| [🧐Sprint 회의]() | **16**<br/>[🌞Scrum]() <br/>[🌛Wrap-up]() | **17**<br/>[🌞Scrum]() <br/>[🌛Wrap-up]()                      | **18**<br/>[🌞Scrum]() <br/>[🌛Wrap-up]()                      | **19**<br/>[🌞Scrum]() <br/>[🌛Wrap-up]()                      | **20**<br/>[🌞Scrum]() <br/>[🌛Wrap-up]() | [🤔Sprint 회고]() |
