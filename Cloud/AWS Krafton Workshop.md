#cloud
## Storage
### Storage Type
- Block Storage: 데이터를 일정 크기의 블록으로 나누어 저장
- File Storage: 디렉토리 구조로 파일을 저장
- Object Storage: REST 기반의 API 호출을 통해 데이터에 접근. (확장성 높음, 다양한 데이터를 넣을 수 있기 때문에 사용성이 좋음.)
- SAN(Storage Area Network)
- NAS(Network Attached Storage)
### AWS는 광범위한 스토리지 포트폴리오 제공
- S3: Simple Storage Service
- EBS: Elastic Block Service
## S3
### Amazon Simple Storage Service(S3)
- 무제한에 가까운 스토리지 용량과 오브젝트
- 데이터 레이크 구축
- 자동화된 비용 절감
### 원하는 오브젝트 스토리지 클래스
 - 비용을 온 몸을 비틀어 적용하기 위해 클래스가 존재.
### Amazon S3 데이터 복제
- 만약 여러 리전에서 서비스를 하는 중, 서울에 있는 S3 데이터를 읽으려고 치면 15분만에 복제 제공.
### S3 Storage Lens
- 사용중인 오브젝트 스토리지에 대한 가시성을 제공하는 분석 솔루션.
- 활동 지표와 대화형 대시보드를 통해 스토리지를 이해, 분석 및 최적화하여 오가니제이션, 특정 어카운트, 레지온, 버킷 등에 대한 데이터를 집게할 수 있음.
## Blcok Storage
### Summary
- Amazon EBS 
- Amazon EFS
- Amazon S3

## Database in AWS
목차
- RDS
- Aurora
- DynamoDB
- ElastiCache
### 완전 관리형 데이터베이스 서비스
- 자체 관리형: 아래 스텝 외에는 AWS가 자동 관리
- 스키마 설계
- 쿼리 생성
- 쿼리 최적화
### 목적에 맞는 데이터베이스 사용
- Relational: RDB. Aurora, RDS
- Key-value: json. DynamoDB
- Document: DocumentDB
## RDS
### 다양한 AWS 관리 서비스와 통합
### 성능 개선 도우미
## Aurora
### Aurora: 클라우드용으로 구축된 MySQl 및 PostgreSQL 호환 연계형 DB
- 완전 관리형
- 성능 & 확장성
- 가용성  & 내구성
### 오로라 아키텍처
- Shared Storage Volume: 데이터베이스를 분산 처리, 성능을 올려줌.
- 로그 기반 분산형 스토리지
## DyanmoDB
- No SQL로 해보고 싶으면 이거 해보세요

## ElastiCaching
### 캐싱이 필요한 이유
- 빠름: 메모리는 빠르다.
- 예측 가능함: 디스크 탐색 시간이 안 든다.
![[Screenshot 2025-06-18 at 2.55.18 PM.png]]


