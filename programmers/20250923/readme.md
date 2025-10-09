## 문제: 사원 정보 조회하기 (기본 SELECT 문제)

사원(emp) 테이블 정보  
empno ename job sal deptno  
7369 SMITH CLERK 800 20  
7499 ALLEN SALESMAN 1600 30  
7521 WARD SALESMAN 1250 30  

## 문제
모든 사원의 이름(ename)과 직업(job)을 조회하세요.  

부서번호가 30인 사원의 이름(ename)만 조회하세요.  

## 풀이

```sql
-- 1. 모든 사원의 이름과 직업 조회
SELECT ENAME, JOB
FROM EMP;

-- 2. 부서번호가 30인 사원의 이름만 조회
SELECT ENAME
FROM EMP
WHERE DEPTNO = 30;