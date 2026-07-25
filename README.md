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