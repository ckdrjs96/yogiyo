# yogiyo

## project
요기요 리뷰를 리뷰이벤트 내용을 이용하여 신뢰도 점수를 책정하기

## Date
20.12 ~ 21.2

## Library
selenium, beautifulsoup, konlpy.okt

## Order of operation
craw_shop : 해당학교 주소에서 배달 가능한 전체 음식점 이름,별점,정보란  내용 수집
make_catagory : craw_shop에서 저장한 음식점들을 리뷰이벤트 조건에 따라 카테고리화
craw_review : 카테고리별로 음식점의 리뷰와 사진들을 수집
score_make_EDA : 신뢰도점수를 2가지 방식으로 부여 
