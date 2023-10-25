# Data-Pipeline-DBT-Airflow-on-GCP


# Data Architecture
![image](https://github.com/hanjhoon/Data-Pipeline-DBT-Airflow-on-GCP/assets/121271030/94f08a59-262f-482a-b51d-35cfcfdcdc8b)


# Tools
1. BigQuery (GCP) - BigQuery는 Google Cloud에서 제공하는 완전히 관리되고 서버리스한 데이터 웨어하우스 및 분석 플랫폼입니다. 이는 대규모 데이터셋을 확장 가능하고 비용 효율적으로 저장하고 분석하기 위해 설계되었습니다. BigQuery는 Google Cloud 플랫폼 (GCP)의 일부이며 비즈니스 인텔리전스, 데이터 웨어하우징, 데이터 탐색 및 머신러닝을 비롯한 다양한 데이터 처리 및 분석 작업에 자주 사용됩니다.

2. SODA - SODA (Scalable Open Data Automation)는 데이터의 유효성 및 품질 검사를 확장 가능하고 효율적으로 자동화하기 위해 설계된 데이터 품질 프레임워크와 도구 모음입니다. 이것은 주로 대규모 데이터셋의 품질, 무결성 및 규정 준수를 확인하는 데 사용됩니다. SODA는 특정 프로그래밍 언어나 기술 스택에 특정하지 않으며 다양한 데이터 원본과 형식에 적용할 수 있습니다.

3. DBT - dbt는 "데이터 빌드 도구"의 약어로 현대 데이터 분석 및 엔지니어링을 위한 오픈 소스 명령줄 도구 및 모델링 프레임워크입니다. 이는 데이터 분석가와 데이터 엔지니어가 데이터 웨어하우스 내에서 데이터 변환과 모델링을 관리하는 데 도움을주기 위해 설계되었습니다. dbt는 데이터 변환과 모델링을 소프트웨어 개발의 최상의 관행과 유사하게 버전 관리, 테스트 가능하고 유지 가능한 방식으로 가능하게 하는 데 중점을 둡니다.

4. Astro CLI - Astro CLI는 데이터 오케스트레이션을 위한 명령줄 인터페이스입니다. 이는 Astronomer 스위트의 일부이며 Apache Airflow를 쉽게 시작할 수있도록 하고 모든 Astronomer 제품과 함께 사용할 수 있습니다. Astro CLI의 주요 기능 중 하나는 로컬 컴퓨터에서 Airflow를 실행할 수있는 능력입니다. Astro 프로젝트에는 DAG 파일, 플러그인 및 종속성을위한 전용 폴더를 포함하여 Airflow를 실행하는 데 필요한 파일 집합이 포함되어 있습니다.

5. Metabase - Metabase는 조직이 데이터를 쉽게 시각화하고 분석할 수있게 하는 오픈 소스 비즈니스 인텔리전스 (BI) 및 데이터 분석 도구입니다. 이는 기술적 또는 SQL 지식이 깊이 필요하지 않고 차트, 대시 보드 및 보고서를 만들기 위한 사용자 친화적인 인터페이스를 제공합니다. Metabase는 비즈니스 분석가, 데이터 분석가 및 비기술 스테이크 홀더를 포함한 조직 내 다양한 사용자에게 데이터 탐색과 보고를 액세스 할 수있게 설계되었습니다.

6. Visual Code Studio - Visual Studio Code, 종종 VS Code로 약칭되며 Microsoft에서 개발 한 무료 오픈 소스 코드 편집기입니다. 이는 개발자 사이에서 가장 인기있는 코드 편집기 중 하나가되었으며 다양한 프로그래밍 언어 및 플랫폼에서 코드를 작성하고 편집하는 데 널리 사용됩니다. VS Code는 유연성, 확장성 있는 확장 마켓플레이스 및 다양한 기능으로 유명하며 다양한 개발 작업에 적합합니다.

7. Docker - Docker는 개발자가 응용 프로그램과 해당 종속성을 가볍게 컨테이너로 패키지화하고 배포 할 수있게하는 플랫폼 및 기술입니다. 이러한 컨테이너는 응용 프로그램 및 실행에 필요한 모든 라이브러리, 종속성 및 구성을 캡슐화하는 격리된 환경입니다. Docker 컨테이너는 일관성과 이식성을 제공하여 다양한 환경 (개발, 테스트 및 프로덕션을 포함)에서 응용 프로그램을 개발, 배포 및 확장하는 것을 더 쉽게 만듭니다.

8. Git 버전 관리 - Git은 소프트웨어 개발 및 기타 협업 프로젝트에서 소스 코드, 문서 및 다른 유형의 파일의 변경 사항을 추적하기 위해 널리 사용되는 분산 버전 관리 시스템 (VCS)입니다. Git과 같은 버전 관리 시스템은 개발자 및 팀이 프로젝트 파일의 변경 내역을 관리하고 소프트웨어 개발 및 기타 창조적인 작업에 효과적으로 협력하는 데 도움을줍니다.

# Dataset

Dataset link: [Online Retail Dataset](https://www.kaggle.com/datasets/mashlyn/online-retail-ii-uci)


# Table on DBT
![image](https://github.com/hanjhoon/Data-Pipeline-DBT-Airflow-on-GCP/assets/121271030/3b2e4ebb-85c3-4f3d-86c6-9f924f8b1fa0)
