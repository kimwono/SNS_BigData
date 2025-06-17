# SNS_BigData

📚 **YES24 베스트셀러 크롤링 프로젝트**  
본 프로젝트는 YES24 웹사이트의 베스트셀러 전체 목록을 Selenium을 이용해 자동으로 수집하고, 수집된 데이터를 CSV 파일로 저장하는 크롤러를 구현한 결과입니다.

---

## 📌 프로젝트 개요

- **목표**: YES24 베스트셀러 순위 정보를 페이지별로 수집하여 정리
- **크롤링 대상**: 
  - YES24 베스트셀러
- **수집 항목**:
  - 순위
  - 제목
  - 저자
  - 출판사
  - 가격

---

## 🛠 사용 기술

- Python
- Selenium
- Pandas
- ChromeDriver

---

## 🗂 파일 구성

| 파일명 | 설명 |
|--------|------|
| `sns_final.ipynb` | 크롤링 코드가 포함된 Jupyter Notebook 파일 |
| `yes24_bestseller_full.csv` | 크롤링한 전체 베스트셀러 정보 CSV 결과 파일 |
