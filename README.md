
# Flask_FirstStep ML Project
find what you are looking for travel place

## Description
- 문제 정의 
	- 1. 연령층이 높을 수록 인터넷 검색을 어려워하는 경향이 강하다.
	- 2. 내가 다녀왔던 지역과 비슷한 느낌의 여행지를 찾고 싶다.
	- 3. 누구나 쉽게 여행지를 정보를 찾아야 한다.

### Service INFO
홈페이지에 접속 이전에 방문한 혹은 방문하고 싶은 여행지를 검색하면 그 여행지와 비슷한 여행지를 추천해 주는 시스템입니다.  
간단하게 여행지명만 입력하면 사용할 수 있도록 개발하였습니다.

ML model CountVectorizer를 사용해 Text 기반으로 cosine similarity기반 추천 시스템입니다.

### Pipeline
![6  파이프 라인](https://user-images.githubusercontent.com/98085184/230550401-ab6b7d75-5832-4d32-bddd-c0e392ac402f.png)

### Data Source (Crawling)
- 대한민국 구석구석
	- https://korean.visitkorea.or.kr/main/main.do#home 
- Tour API
	- https://api.visitkorea.or.kr/#/ 

### Web Page Image
![image](https://user-images.githubusercontent.com/98085184/230550928-5f6ace42-75f6-4ff3-96fa-4b71c7554d70.png)
![image](https://user-images.githubusercontent.com/98085184/230551014-95bf65b5-42cf-4ccd-82b0-8e74c391f825.png)
## Environment
> Python Version 3.8

## Prerequisite
> Python ENV
>
> pip install -r requirements.txt
>
> export FLASK_APP=firststep FLASK_ENV=development
>
> flask run
