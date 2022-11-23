# AI 부트업

네트워크 / 파일 / 이미지 모듈 중심

## 리뷰: 프로그램 작성 예시
 - [P-데이터선언_함수_클래스.ipynb](notebooks/P-데이터선언_함수_클래스.ipynb)

---

# 1. 컴프리헨션

  - 컴프리헨션 학습 https://wikidocs.net/22795

# 2. Crawling

## 1. Web 기본
   - HTTP / HTML / CSS / MIME Type
   - 강의중 노트: [Webcrawling_HTTP_HTML.ipynb](notebooks/Webcrawling_HTTP_HTML.ipynb)
## 2. Python 네트워크 (http)
   - requests 모듈: [데이터크롤링1-02requests.ipynb](notebooks/데이터크롤링1-02requests.ipynb)
   - Beautifulsoup 모듈: [데이터크롤링1-03BS4_Start.ipynb](notebooks/데이터크롤링1-03BS4_Start.ipynb)
   - 수업중 실습: 네이버 영화랭킹 날짜별 출력 [실습_크롤링_영화랭킹_1122.md](notebooks/실습_크롤링_영화랭킹_1122.md)

## 3. 파일 저장

CSV 파일 읽고/쓰기:
   - https://docs.python.org/ko/3/library/csv.html
   - https://wikidocs.net/80822
   - Sample file:
       - https://github.com/UCLSPP/datasets/blob/master/data/Credit.csv

JSON 파일 읽고/쓰기:
   - https://wikidocs.net/67980 
   - json 쓰기: https://wikidocs.net/126088

### "실습1" 네이버 상영자/예정작 크롤링 결과 csv 저장

1. 제목 / { 네티즌 평점/참여 인원 } / {기자 평점 / 인원 } / 감독 / 출연진 / 개봉일
1. `함수` 적용해 보세요
1. **완료시** 과제폴더 오늘날자에 `이름_영화상영작_csv.ipynb` 형식으로 업로드.
> **결과 샘플**: [김예원_상영작_csv_test.ipynb](notebooks/김예원_상영작_csv_test.ipynb)


### "실습2" 영화랭킹의 5개 날짜 페이지 파싱한 결과 CSV 저장
 - **완료시** 과제폴더 오늘날자에 `이름_영화랭킹_csv.ipynb` 형식으로 업로드.
 - 현재 랭킹 페이지: https://movie.naver.com/movie/sdb/rank/rmovie.naver
 - 이전 날짜 랭킹 페이지 : https://movie.naver.com/movie/sdb/rank/rmovie.naver?sel=cnt&tg=0&date=20221120
     - `URL?date=yyyymmdd` 형식


4. 크롤링 실습
   - 네이버 뉴스: [데이터크롤링ex-네이버뉴스(csv)](notebooks/데이터크롤링ex-네이버뉴스(csv).ipynb)
   - "실습": 함수 이용 클롤링 코드 수정.

# 3. Open API 사용
   1. 네이버 Open API: 검색 / 블로그 등...
   2. 공공데이터 Open API: data.go.kr
        - requests 이용 POST 방식


# 4. Numpy 와 Pandas
   1. [NumPy](notebooks/2-01NumPy1-Tutorial_0.ipynb)
   2. [Pandas Series](notebooks/2-04Pandas_Series-0.ipynb)
   3. [Pandas Dataframe](notebooks/2-05Pandas_DataFrame-0.ipynb)
   4. "실습": KRX 주식시세 크롤링
        - requests 이용 POST 방식
   5. 시각화 도구: Matplotlib, Seaborn, Plotly


# 5. 정규표현식


# 6. 지도: Follium

<!--
- Image module: Pillow
- NumPy, Pandas, Matplotlib, Seaborn
-->
