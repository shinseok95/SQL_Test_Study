# SQL_Test_Study

> SQL 코딩테스트를 대비한 문제 풀이를 정리하는 Repository입니다.<br>

# 목차

- [기본 SQL 문법](#기본-SQL-문법)
  - [DDL](#DDL(Data-Definition-Language))
  - [DML](#DML(Data-Manipulation-Language))
  - [DCL](#DCL(Data-Control-Language))
- [SELECT](#SELECT)

## 기본 SQL 문법
 
### DDL(Data Definition Language)

- 정의
  - 데이터를 저장하는 DB 및 Table을 생성, 삭제하는 명령어

- 종류 
  - `CREATE`: 생성  
  - `DROP`: 삭제  
  - `ALTER`: 변경  

### DML(Data Manipulation Language)

- 정의
  - Table의 행을 검색하거나 변경하기 위한 것이다.
- 종류
  - `SELECT`: 행 검색
  - `INSERT`: 신규 행 등록   
  - `DELETE`: 행 삭제


### DCL(Data Control Language)

- 정의
  - DB에서 처리한 변경 내용을 확정하거나 취소
  - 사용자에게 처리 권한을 부여, 회수

- 종류
  - `COMMIT`: 변경 내용 저장
  - `ROLLBACK`: 변경 내용 취소   
  - `GRANT`: 처리 권한 부여  
  - `REVOKE`: 처리 권한 회수
  
## SELECT

### 상위 n개 출력하기

```sql
SELECT NAME 
  FROM ANIMAL_INS 
  LIMIT n;
```
