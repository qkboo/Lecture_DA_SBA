# AI 부트업

네트워크 / 파일 / 이미지 모듈 중심

## 리뷰: 프로그램 작성 예시
 - [P-데이터선언_함수_클래스.ipynb](notebooks/P-데이터선언_함수_클래스.ipynb)

---


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


## 4. 크롤링 실습
   - 네이버 증권: [데이터크롤링ex네이버_KOSPI200](notebooks/데이터크롤링ex네이버_KOSPI200_0.ipynb)
   - 네이버 뉴스: [데이터크롤링ex-네이버뉴스(csv)](notebooks/데이터크롤링ex-네이버뉴스(csv).ipynb)
   - "실습": 함수 이용 클롤링 코드 수정.


# 3. Open API 사용
   1. 공유폴더
       - `핀테크2-01REST_API사용202211.pdf`
   2. 네이버 Open API: 검색 / 블로그 등...
       - requests 이용 POST 방식
   3. 공공데이터 Open API: data.go.kr
       - requests 이용 POST 방식
   4. 금융 API
       - `핀테크2-02OpenBanking-202211.pdf`
       - [오픈뱅킹-NH.ipynb](notebooks/오픈뱅킹-NH.ipynb)

# 4. Numpy 와 Pandas
   1. [NumPy](notebooks/2-01NumPy1-Tutorial_0.ipynb)
   2. [NumPy 기본연산](notebooks/2-01NumPy2-Op.ipynb)
   3. [Pandas Series](notebooks/2-04Pandas_Series-0.ipynb)
   4. [Pandas Dataframe](notebooks/2-05Pandas_DataFrame-0.ipynb)
   5. 외부자료 실습:
       - [2-Pandas_외부자료_data.zip](notebooks/2-Pandas_외부자료_data.zip)
       - [2-Pandas_외부자료.ipynb](notebooks/2-Pandas_외부자료.ipynb)

   5. "실습": KRX 주식시세 크롤링
        - requests 이용 POST 방식
   6. 시각화 도구: Matplotlib, Seaborn, Plotly


---
<!-- 
### "11/24 과제" 네이버 뉴스
   - 네이버 뉴스 / 대분류 / 중분류 및 기사 내용 텍스트 크롤링
       - `대분류/중분류/순번/기사제목/날짜/기사내용` 등을 수집해 CSV 저장
   - `함수` 사용
   - **완료시** 과제폴더 오늘날자에 `이름_네이버뉴스.ipynb` 형식으로 업로드.
-->

### "11/23 과제" 멜론
   - 멜론 최신 100곡 크롤링: 'https://www.melon.com/chart/index.htm'
       - `순위/곡정보/앨범/좋아요` 수집해 CSV 저장
   - `함수` 사용
   - **완료시** 과제폴더 오늘날자에 `이름_멜론.ipynb` 형식으로 업로드.




# 5. 정규표현식


# 6. 지도: Follium




<!--
- Image module: Pillow
- NumPy, Pandas, Matplotlib, Seaborn
-->
