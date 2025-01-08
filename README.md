# 메이플스토리 상위 유저 데이터 시각화 프로젝트

이 프로젝트는 **메이플스토리** 상위 유저 데이터를 분석하고 시각화하는 프로젝트입니다. **Jupyter Notebook**을 사용하여 데이터를 분석하고, **Tableau**를 이용해 시각화 작업을 진행하였습니다.

## 프로젝트 파일

- **CSV 데이터 파일**: 메이플스토리 상위 유저 데이터를 포함한 CSV 파일입니다. 게임 닉네임, 직업, 길드, 랭킹, 아이템 환산, 헥사환산 등의 정보를 포함하고 있습니다.
  - [CSV 데이터 파일 보기](https://github.com/ManUOnana/-_-/blob/main/%ED%97%A5%EC%82%AC%EB%9E%AD%ED%82%B9.csv)

- **Jupyter Notebook 코드**: 메이플스토리 상위 유저 데이터를 분석하고, Tableau 시각화를 위한 데이터 전처리 및 분석 코드를 포함하고 있습니다.
  - [Jupyter Notebook 보기](https://github.com/ManUOnana/-_-/blob/main/Hexa_Ranking-checkpoint.ipynb)

이 노트북에서는 **웹 스크래핑**을 사용하여 **환산주스텟** 웹사이트에서 **헥사환산 100,000 이상**인 상위 유저 데이터를 추출하고, 이를 **CSV 파일**로 저장했습니다. 이 과정에서 **Selenium**을 이용해 페이지를 자동으로 탐색하고, **BeautifulSoup**을 통해 필요한 데이터를 추출했습니다.

### 사용된 기술:
- **Selenium**: 웹 페이지 자동화 및 데이터 추출
- **BeautifulSoup**: HTML 파싱
- **CSV**: 추출된 데이터 저장

### 주요 작업:
- **페이지 자동화**: Selenium을 이용해 각 페이지를 자동으로 탐색하며 데이터를 수집.
- **데이터 필터링**: 헥사환산이 100,000 이상인 유저만 필터링하여 저장.
- **CSV 저장**: 추출한 데이터를 CSV 파일로 저장하여 분석 가능하도록 처리.

- **Tableau 대시보드**: Tableau로 시각화한 메이플스토리 상위 유저 데이터의 시각화 대시보드를 아래 링크에서 확인할 수 있습니다.
  - [Tableau 대시보드 보기](https://public.tableau.com/app/profile/.49798823/viz/_17362764297690/1_1)

## 프로젝트 목표
이 프로젝트의 목표는 메이플스토리 상위 유저들의 데이터를 분석하고, 그 분석 결과를 **Tableau**를 통해 시각적으로 표현하는 것입니다.
