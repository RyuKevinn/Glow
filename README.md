# Glow

Link  - https://ryukevinn.github.io/React_Glow/


---------------------------------

프로젝트 명 : Glow Resort

---------------------------------

작업기간 : 2022_03_16 - 2022_03_25

---------------------------------

사용 에디터 : VSC (Visual Studio Code)

---------------------------------

사용 프로그램 언어 : React.js

---------------------------------

사용 기술 및 데이터

1. API data 

            - current weather data = https://api.openweathermap.org/data/2.5/weather?q=seoul&units=metric&appid=5eb107829897c53a70f4025f453107d9
 
            - week weather data = https://api.openweathermap.org/data/2.5/forecast?q=seoul&units=metric&cnt=35&appid=5eb107829897c53a70f4025f453107d9
         
2. DatePicker (React-Datepicker)
3. Google Map
4. AOS animation 
5. HashRouter (React-Router-Dom)
6. Link (React-Router-Dom)
7. useEffect (React)
8. useState (React)
9. axios (axios)
10. React Icon (React-Icons)
11. Styled-Components
12. classnames
13. switch/case
---------------------------------

API 데이터 정보

<h1>Current Weather<h1>      
            -  API Link = https://api.openweathermap.org/data/2.5/weather?q=seoul&units=metric&appid=5eb107829897c53a70f4025f453107d9

            
              1. [Json Data Sample]
 ![KakaoTalk_20220415_122918422](https://user-images.githubusercontent.com/96170774/163513981-08232094-4cfd-4c97-b6c6-a42cf4cff393.png)
                      
              2. [In Web]
 ![zzzzzzz](https://user-images.githubusercontent.com/96170774/163513985-2d4e9c7f-757f-4957-b7e1-8306bf5886af.png)
                       





---------------------------------

프로젝트 진행 사항

  ★어려웠던 부분
      - API 데이더 호출 시 순수 배열 데이터가 아닌 점
      
            해결방안
            
              1. [ 추출 데이터 양이 적은 current weather data 의 경우 각 항목을 직접 지정하여 useState로 추출]
![KakaoTalk_20220328_113206504](https://user-images.githubusercontent.com/96170774/160316814-110dc006-fdb0-4684-b11c-e5a444ca4e1b.png)



              
              
              
              
              
              2. [ 데이더 양이 많고 일부 데이터만 추출 해야 하는 week weather data 의 경우 아래 이미지 참조]
![KakaoTalk_20220328_112236801](https://user-images.githubusercontent.com/96170774/160316129-6ae86815-ac84-470c-a4c1-2bbfe71e2c93.png)





