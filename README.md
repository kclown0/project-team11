# 기업연계 project

## 프로젝트 설명
- AWS 클라우드 환경을 활용해 ETL(추출, 변환, 로드) 전 과정을 구축하는 프로젝트
- S3(원본데이터) >> ERM(파티셔닝 및 버킷팅, 압축) >> S3(Transform)
- Athena >> SuperSet 연동 및 시각화 순으로 작업 진행
- Airflow를 통해 프로젝트 자동화 진행

## 프로젝트 기간
2023.11.09 - 2023.12.15

## 아키텍처
![image](https://github.com/yeardream-de-project-team11/project-team11/assets/104144701/599d8a4a-4499-4121-a609-efc6966a3728)

[역할] 

- 팀장으로써 기업 담당자와의 커뮤니케이션 담당
- EMR 파티셔닝/압축 단계 customer script 작성
- airflow athean table dag 작성
- superset athena 연동 하는 부분을 담당]
