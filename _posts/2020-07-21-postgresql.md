---
title : "PostgreSQL 실습 환경 설정"
category : 
    - postgresql
tag : 
    - postgresql
    - sql
author_profile : true
toc : true
---


SQL/DB 강의 수강을 위해 PostgreSQL을 설치하고 샘플 DB를 구축한 뒤 DBeaver를 설치했다

강의를 보면서 설치했는데 헷갈리고 잘 안돼서...

[PostgreSQL tutorial](https://www.postgresqltutorial.com/install-postgresql-macos/) 페이지를 참고하여 설치했다

---

### Sample DB 
튜토리얼에서 제공하는 [샘플DB 저장하기](https://www.postgresqltutorial.com/postgresql-sample-database/) 


### PostgreSQL
- multi-version concurrency control(MVCC) 지원
- C/C++, Java 등의 프로그래밍 언어 연동 지원
- 확장성이 좋음
- 오픈소스

#### 설치하기
[PostgreSQL downloads](https://www.enterprisedb.com/downloads/postgres-postgresql-downloads)

나는 Mac OS에 지원하는 가장 최신 버전인 12.3을 설치했다

튜토리얼을 보고 설치를 마치면 아래처럼 설치가 되어있다

<img width="710" alt="스크린샷 2020-07-21 오후 11 20 52" src="https://user-images.githubusercontent.com/57264003/88066685-00b51380-cba9-11ea-93bc-f6aee80b74be.png">

#### 접속하기

**pgAdmin 4**를 실행하여 접속한다

---

### DBevear 

- DB Tool
- 다양한 DB와 연동 가능
- ERD를 간단하게 볼 수 있음

#### 설치하기
[DBevear downloads](https://dbeaver.io/download/)

귀여운 비버 아이콘이 생겼다 :-)

<img width="140" alt="스크린샷 2020-07-21 오후 11 21 11" src="https://user-images.githubusercontent.com/57264003/88066673-fe52b980-cba8-11ea-8d7d-fb8c98c5769a.png">