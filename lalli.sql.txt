SQL> spool
currently spooling to D://lalli.sql.txt
SQL> SELECT LAST_NAME, SALARY
  2  FROM EMPLOYEES
  3  WHERE SALARY>12000;

LAST_NAME                     SALARY                                            
------------------------- ----------                                            
King                           24000                                            
Kochhar                        17000                                            
De Haan                        17000                                            
Greenberg                      12008                                            
Russell                        14000                                            
Partners                       13500                                            
Hartstein                      13000                                            
Higgins                        12008                                            

8 rows selected.

SQL> SELECT LAST_NAME, DEPARTMENT_ID
  2  FROM EMPLOYEES
  3  WHERE EMPLOYEE_ID = 176;

LAST_NAME                 DEPARTMENT_ID                                         
------------------------- -------------                                         
Taylor                               80                                         

SQL> SELECT LAST_NAME, SALARY
  2  FROM EMPLOYEES
  3  WHERE SALARY < 5000
  4  OR SALARY > 12000;

LAST_NAME                     SALARY                                            
------------------------- ----------                                            
King                           24000                                            
Kochhar                        17000                                            
De Haan                        17000                                            
Austin                          4800                                            
Pataballa                       4800                                            
Lorentz                         4200                                            
Greenberg                      12008                                            
Khoo                            3100                                            
Baida                           2900                                            
Tobias                          2800                                            
Himuro                          2600                                            

LAST_NAME                     SALARY                                            
------------------------- ----------                                            
Colmenares                      2500                                            
Nayer                           3200                                            
Mikkilineni                     2700                                            
Landry                          2400                                            
Markle                          2200                                            
Bissot                          3300                                            
Atkinson                        2800                                            
Marlow                          2500                                            
Olson                           2100                                            
Mallin                          3300                                            
Rogers                          2900                                            

LAST_NAME                     SALARY                                            
------------------------- ----------                                            
Gee                             2400                                            
Philtanker                      2200                                            
Ladwig                          3600                                            
Stiles                          3200                                            
Seo                             2700                                            
Patel                           2500                                            
Rajs                            3500                                            
Davies                          3100                                            
Matos                           2600                                            
Vargas                          2500                                            
Russell                        14000                                            

LAST_NAME                     SALARY                                            
------------------------- ----------                                            
Partners                       13500                                            
Taylor                          3200                                            
Fleaur                          3100                                            
Sullivan                        2500                                            
Geoni                           2800                                            
Sarchand                        4200                                            
Bull                            4100                                            
Dellinger                       3400                                            
Cabrio                          3000                                            
Chung                           3800                                            
Dilly                           3600                                            

LAST_NAME                     SALARY                                            
------------------------- ----------                                            
Gates                           2900                                            
Perkins                         2500                                            
Bell                            4000                                            
Everett                         3900                                            
McCain                          3200                                            
Jones                           2800                                            
Walsh                           3100                                            
Feeney                          3000                                            
OConnell                        2600                                            
Grant                           2600                                            
Whalen                          4400                                            

LAST_NAME                     SALARY                                            
------------------------- ----------                                            
Hartstein                      13000                                            
Higgins                        12008                                            

57 rows selected.

SQL> SELECT LAST_NAME, JOB_ID, HIRE_DATE
  2  FROM EMPLOYEES
  3  WHERE UPPER(LAST_NAME) = 'MATOS'
  4  OR UPPER(LAST_NAME) = 'TAYLOR';

LAST_NAME                 JOB_ID     HIRE_DATE                                  
------------------------- ---------- ---------                                  
Matos                     ST_CLERK   15-MAR-06                                  
Taylor                    SA_REP     24-MAR-06                                  
Taylor                    SH_CLERK   24-JAN-06                                  

SQL> spool off
SQL> SELECT LAST_NAME EMPLOYEE, SALARY MONTHLY_SALARY
  2  FROM EMPLOYEES
  3  WHERE DEPARTMENT_ID = 20 OR DEPARTMENT_ID = 50
  4  AND SALARY BETWEEN 5000 AND 12000;

EMPLOYEE                  MONTHLY_SALARY                                        
------------------------- --------------                                        
Weiss                               8000                                        
Fripp                               8200                                        
Kaufling                            7900                                        
Vollman                             6500                                        
Mourgos                             5800                                        
Hartstein                          13000                                        
Fay                                 6000                                        

7 rows selected.

SQL> SELCT LAST_NAME, JOB_ID
SP2-0734: unknown command beginning "SELCT LAST..." - rest of line ignored.
SQL> SELECT LAST_NAME, JOB_ID
  2  FROM EMPLOYEES
  3  WHERE LOWER(MANAGER_ID) = 'null';

no rows selected

SQL> SELECT LAST_NAME
  2  FROM EMPLOYEES
  3  WHERE LAST_NAME LIKE '__a%';

LAST_NAME                                                                       
-------------------------                                                       
Grant                                                                           
Grant                                                                           
Whalen                                                                          

SQL> SELECT LAST_NAME EMPLOYEE, SALARY MONTHLY_SALARY, COMMISSION_PCT
  2  FROM EMPLOYEES
  3  WHERE COMMISSION_PCT = 0.2;

EMPLOYEE                  MONTHLY_SALARY COMMISSION_PCT                         
------------------------- -------------- --------------                         
Zlotkey                            10500             .2                         
Olsen                               8000             .2                         
Cambrault                           7500             .2                         
Bloom                              10000             .2                         
Fox                                 9600             .2                         
Taylor                              8600             .2                         
Livingston                          8400             .2                         

7 rows selected.

SQL> spool off
