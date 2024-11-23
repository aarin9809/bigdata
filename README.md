# 국내 병원 및 의원의 수와 종류에 대한 분석
## 대한민국 최고의 사짜 직업 중 하나 '의사'
------
### 주제 선정 이유
대한민국에서 최고 대우를 받는 직업이 있다. '사'짜 직업이 들어간 직업 중 우리 사회에 없어서는 안될 의사다.

그럼 이 매년 배출되는 의사들은 다 어디서 일하고 어떤 전문의들이 많고 병원은 얼마나 많을까?

### 데이터 수집
돌아댕기면서 일일이 병원을 셀 수 없어서 DATA.go.kr(공공데이터포털)에서 csv 파일을 다운받았다. 등록일은 2024.02.01이다. 2023년까지의 데이터가 집계된 자료인거같다.

### 프로젝트 목적
- 전국 병원 및 의원의 분포와 종류를 분석하여 지역별 의료 접근성을 파악한다.
- 진료 과목별로 어떤 전문의가 많이 활동하는지 조사한다.
- 연도별 병원 개설 추이를 분석하여 의료시설 증가율을 확인한다.
- 시군구별로 병원 밀집도를 분석하여 의료 취약 지역을 식별한다.

### 사용된 기술 및 도구
- **Python 라이브러리**:
  - `pandas`: 데이터 전처리 및 분석
  - `matplotlib`, `seaborn`: 데이터 시각화
  - `collections.Counter`: 단어 빈도 분석
- **Jupyter Notebook**: 데이터 분석 및 시각화
- **Google Colab**: 클라우드 환경에서의 데이터 분석

### 분석 과정
1. **데이터 로드 및 전처리**:
   - 공공데이터포털에서 제공된 CSV 파일을 로드.
   - 불필요한 열 제거, 결측값 처리, 날짜 데이터 변환.
   
2. **탐색적 데이터 분석 (EDA)**:
   - 병원 종류별 개수와 지역별 분포 파악.
   - 주요 진료 과목의 빈도 분석.
   - 연도별 병원 개설 추이 분석.

3. **시각화**:
   - 지역별 병원 분포 히트맵.
   - 진료 과목별 빈도 파이 차트.
   - 병원 이름에서 많이 사용된 단어 워드클라우드.

4. **결론 도출**:
   - 지역별 의료시설 부족 지역 확인.
   - 특정 전문의(예: 내과, 소아과) 활동 지역 분석.
   - 병원 개설 연도의 변화 추이 파악.

['병원 및 의원 데이터 분석' pandas 활용 데이터 분석, matplotlib 활용, 데이터 시각화 및 결론 도출](https://github.com/aarin9809/bigdata/blob/main/hospital_data_analysis_final.ipynb)
