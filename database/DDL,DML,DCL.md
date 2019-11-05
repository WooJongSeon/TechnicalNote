# **DDL,DML,DCL**

## 작성자
[![tdm1223](https://avatars1.githubusercontent.com/u/21440957?s=100&v=4)](https://github.com/tdm1223)

## DDL(데이터 정의어)
- 데이터베이스를 정의하는 언어
- 데이터 생성, 수정, 삭제 등 데이터의 골격을 결정한다.

### DDL 종류
1. CREATE
- 데이터베이스, 테이블 등을 **생성**하는 명령어

2. ALTER
- 테이블을 **수정**하는 명령어

3. DROP
- 데이터베이스, 테이블을 **삭제**하는 명령어

4. TRUNCATE
- 테이블을 **초기화**하는 명령어

## DML(데이터 조작어)
- 정의된 데이터베이스에 입력된 레코드를 조회, 수정, 삭제할때 사용하는 명령어
- 데이터베이스 사용자가 저장된 데이터를 실질적으로 처리하는데 사용한다.
- 데이터베이스 사용자와 데이터베이스 관리시스템 간의 인터페이스를 제공한다.
- [DML 사용 예제](https://github.com/jobhope/TechnicalNote/blob/master/database/DB%20%EC%BF%BC%EB%A6%AC%EB%AC%B8%20%EC%A0%95%EB%A6%AC.md)

### DML 종류
1. SELECT
- 데이터를 **조회**하는 명령어

2. INSERT
- 데이터를 **삽입**하는 명령어

3. UPDATE
- 데이터를 **수정**하는 명령어

4. DELETE
- 데이터를 **삭제**하는 명령어

## DCL(데이터 제어어)
- 데이터베이스에 접근하거나 객체에 권한을 줄때 사용하는 명령어
- 데이터를 제어하는 언어
- 데이터의 보안, 무결성, 회복, 병행 수행제어 등을 정의하는데 사용

### DCL 종류
1. GRANT
- 데이터베이스 사용자에게 작업에 대한 **수행권한을 부여**할때 사용하는 명령어

2. REVOKE
- 데이터베이스 사용자에게 작업에 대한 **수행권한을 박탈, 회수**할때 사용하는 명령어

3. COMMIT
- 트랙젝션의 작업이 정상적으로 완료되고 데이터베이스에 **작업 결과를 반영**하는 명령어

4. ROLLBACK 
- 트랙젝션의 작업이 비정상적으로 종료되었을 때 **원래의 상태로 복구** 하는 명령어

###