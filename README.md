# codespace


oracle 리포지토리 만들어서 아래꺼


-- create
CREATE TABLE EMPLOYEE (
  empId NUMBER PRIMARY KEY,
  name VARCHAR2(15) NULL,
  dept VARCHAR2(10) NOT NULL
);

-- insert
INSERT INTO EMPLOYEE VALUES (1, '', 'Sales');
INSERT INTO EMPLOYEE VALUES (2, ' ', 'Accounting');
INSERT INTO EMPLOYEE VALUES (3, 'Ava', 'Sales');

-- fetch 
SELECT * FROM EMPLOYEE;


oracle에서 to_char    +2                    오라클의 TO_CHAR 함수는 날짜나 숫자를 문자열로 바꾸는 함수이며, 날짜 변환과 숫자 변환에 주로 사용합니다.날짜 변환YYYY-MM-DD: 연도-월-일 (예: 2026-07-26)YYYY/MM/DD HH24:MI:SS: 연도/월/일 시:분:초DY 또는 DAY: 요일 (예: 일, 일요일)숫자 변환999,999: 천 단위 콤마와 빈자리 공백 처리 (예: 123,456)000,000: 빈자리를 0으로 채움999.99: 소수점 자리수 지정더 자세한 예제 코드나 특정 포맷 형식이 필요하시면 말씀해 주세요!젠트의 프로그래밍 세상[Oracle] 오라클 TO_CHAR 함수 사용법 완벽한 정리 (날짜포맷, 소수점, 천 ...2020. 7. 23. — 오라클에서 쿼리문을 작성할 때 TO_CHAR() 함수는 날짜, 숫자 등의 값을 문자열로 변환하는 함수이다. 자주 사용하는 기본 함수이므로 아래의 다양한 ...코딩팩토리[Oracle] 오라클 다양한 날짜 / 시간 포맷 변경 (TO_CHAR) 사용법 & 예제2019. 11. 30. — 위와 같이 오라클에서 날짜 포맷팅을 하는 방법은 TO_CHAR함수를 사용하여 특정 FORAMT에 맞춰 출력할 수 있습니다. 사용법은 TO_CHAR(숫자 or 날짜...블로그[오라클/SQL] TO_CHAR (1) 날짜를 다양한 형태의 문자로 바꾸는 방법 : 숫자2020. 12. 23. — TO_CHAR는 숫자 타입이나 날짜 타입의 데이터나 컬럼을 원본 데이터를 바꾸지 않고 문자 타입으로 형변환하여 출력해 주는 함수입니다. ​. ​. 2) ...티스토리[Oracle DB] 오라클 함수 (4) - 단일행 형 변환 함수 (TO_CHAR, TO_NUMBER ...2022. 1. 22. — TO_CHAR 함수는 날짜, 숫자 데이터를 문자 데이터로 변환해 주는 함수입니다. 주로 날짜 데이터에서 문자 데이터로 변환하는 데 많이 사용하며 다음과 ...Naver Blog[OracleDB] 큰 숫자 3자리마다 쉼표 붙이기2020. 2. 4. — 카테고리 이동 기술 Oracle ( 오라클 ) DB에서 큰 숫자에 3자리마다 쉼표를 붙이는 방법에 대해서 알아보겠습니다. TO_CHAR( )함수에 숫자와 포멧(9...    AI 답변에 오류가 있을 수 있습니다. 자세히 알아보기