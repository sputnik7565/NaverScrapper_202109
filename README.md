# NaverScrapper_202109

이 프로젝트는 데이터 수집을 위한 샘플 프로젝트로 입력된 검색어를 네이버에서 검색 후 출력된 첫 페이지의 결과를 엑셀, csv, 텍스트 파일 형식으로 저장합니다.

파이썬 기반 자유 및 오픈 소스 웹 프레임워크 , 주피터 노트북을 사용해 구축된 프로젝트

## Getting Started 
### Dependencies 
* Python3.8 + 
* beautifulsoup4 == 4.6.0
* selenium == 3.141.0
* pandas == 1.2.4
* xlwt == 1.3.0
* 자신의 크롬 버전과 맞는 chromedriver.exe 파일이 NaverScrapper_202109.ipynb 와 같은 경로에 필요 ( 크롬 드라이버 다운로드 https://chromedriver.chromium.org/downloads )


## Usage
네이버 메인 페이지에서 입력된 검색어를 블로그, 뉴스, 카페, 지식백과, 어학사전 중 하나를 선택 해 검색을 실행 한 후 검색 결과를 xlsx, csv, txt 파일로 저장

<details><summary><b>Show instructions</b></summary>

  1. 주피터노트북에서 프로젝트를 실행
  2. 검색어 입력
  3. 다음 메뉴 중 하나 선택
  ```
  [메뉴] 1.블로그  2.뉴스  3.카페  4.지식백과  5.어학사전 (종료. 0)
  ```
  4. 데이터 추출 후 저장 여부 선택
  ```
  추출된 데이터를 파일로 저장하시겠습니까? (Y/N)
  ```
  5. 저장을 선택 했다면 저장 파일 형식 선택
  ```
  [메뉴] 1.txt 2.csv 3.xls 4.전체 저장 (종료: 0)
  ```
  6. 저장 경로 지정 후 저장  

</details>


## Demo

![demo](https://youtu.be/JfjsOP7RzH4)
