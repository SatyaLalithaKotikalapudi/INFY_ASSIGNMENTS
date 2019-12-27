SQL> spool
currently spooling to D://lalli1.sql.txt
SQL> SELECT SYSDATE AS "DATE"
  2  FROM DUAL;

DATE                                                                            
---------                                                                       
27-DEC-19                                                                       

SQL> SELECT EMPLOYEE_ID, LAST_NAME, SALARY, SALARY*(115.5/100) AS "NEW_SALARY"
  2  FROM EMPLOYEES;

EMPLOYEE_ID LAST_NAME                     SALARY NEW_SALARY                     
----------- ------------------------- ---------- ----------                     
        100 King                           24000      27720                     
        101 Kochhar                        17000      19635                     
        102 De Haan                        17000      19635                     
        103 Hunold                          9000      10395                     
        104 Ernst                           6000       6930                     
        105 Austin                          4800       5544                     
        106 Pataballa                       4800       5544                     
        107 Lorentz                         4200       4851                     
        108 Greenberg                      12008   13869.24                     
        109 Faviet                          9000      10395                     
        110 Chen                            8200       9471                     

EMPLOYEE_ID LAST_NAME                     SALARY NEW_SALARY                     
----------- ------------------------- ---------- ----------                     
        111 Sciarra                         7700     8893.5                     
        112 Urman                           7800       9009                     
        113 Popp                            6900     7969.5                     
        114 Raphaely                       11000      12705                     
        115 Khoo                            3100     3580.5                     
        116 Baida                           2900     3349.5                     
        117 Tobias                          2800       3234                     
        118 Himuro                          2600       3003                     
        119 Colmenares                      2500     2887.5                     
        120 Weiss                           8000       9240                     
        121 Fripp                           8200       9471                     

EMPLOYEE_ID LAST_NAME                     SALARY NEW_SALARY                     
----------- ------------------------- ---------- ----------                     
        122 Kaufling                        7900     9124.5                     
        123 Vollman                         6500     7507.5                     
        124 Mourgos                         5800       6699                     
        125 Nayer                           3200       3696                     
        126 Mikkilineni                     2700     3118.5                     
        127 Landry                          2400       2772                     
        128 Markle                          2200       2541                     
        129 Bissot                          3300     3811.5                     
        130 Atkinson                        2800       3234                     
        131 Marlow                          2500     2887.5                     
        132 Olson                           2100     2425.5                     

EMPLOYEE_ID LAST_NAME                     SALARY NEW_SALARY                     
----------- ------------------------- ---------- ----------                     
        133 Mallin                          3300     3811.5                     
        134 Rogers                          2900     3349.5                     
        135 Gee                             2400       2772                     
        136 Philtanker                      2200       2541                     
        137 Ladwig                          3600       4158                     
        138 Stiles                          3200       3696                     
        139 Seo                             2700     3118.5                     
        140 Patel                           2500     2887.5                     
        141 Rajs                            3500     4042.5                     
        142 Davies                          3100     3580.5                     
        143 Matos                           2600       3003                     

EMPLOYEE_ID LAST_NAME                     SALARY NEW_SALARY                     
----------- ------------------------- ---------- ----------                     
        144 Vargas                          2500     2887.5                     
        145 Russell                        14000      16170                     
        146 Partners                       13500    15592.5                     
        147 Errazuriz                      12000      13860                     
        148 Cambrault                      11000      12705                     
        149 Zlotkey                        10500    12127.5                     
        150 Tucker                         10000      11550                     
        151 Bernstein                       9500    10972.5                     
        152 Hall                            9000      10395                     
        153 Olsen                           8000       9240                     
        154 Cambrault                       7500     8662.5                     

EMPLOYEE_ID LAST_NAME                     SALARY NEW_SALARY                     
----------- ------------------------- ---------- ----------                     
        155 Tuvault                         7000       8085                     
        156 King                           10000      11550                     
        157 Sully                           9500    10972.5                     
        158 McEwen                          9000      10395                     
        159 Smith                           8000       9240                     
        160 Doran                           7500     8662.5                     
        161 Sewall                          7000       8085                     
        162 Vishney                        10500    12127.5                     
        163 Greene                          9500    10972.5                     
        164 Marvins                         7200       8316                     
        165 Lee                             6800       7854                     

EMPLOYEE_ID LAST_NAME                     SALARY NEW_SALARY                     
----------- ------------------------- ---------- ----------                     
        166 Ande                            6400       7392                     
        167 Banda                           6200       7161                     
        168 Ozer                           11500    13282.5                     
        169 Bloom                          10000      11550                     
        170 Fox                             9600      11088                     
        171 Smith                           7400       8547                     
        172 Bates                           7300     8431.5                     
        173 Kumar                           6100     7045.5                     
        174 Abel                           11000      12705                     
        175 Hutton                          8800      10164                     
        176 Taylor                          8600       9933                     

EMPLOYEE_ID LAST_NAME                     SALARY NEW_SALARY                     
----------- ------------------------- ---------- ----------                     
        177 Livingston                      8400       9702                     
        178 Grant                           7000       8085                     
        179 Johnson                         6200       7161                     
        180 Taylor                          3200       3696                     
        181 Fleaur                          3100     3580.5                     
        182 Sullivan                        2500     2887.5                     
        183 Geoni                           2800       3234                     
        184 Sarchand                        4200       4851                     
        185 Bull                            4100     4735.5                     
        186 Dellinger                       3400       3927                     
        187 Cabrio                          3000       3465                     

EMPLOYEE_ID LAST_NAME                     SALARY NEW_SALARY                     
----------- ------------------------- ---------- ----------                     
        188 Chung                           3800       4389                     
        189 Dilly                           3600       4158                     
        190 Gates                           2900     3349.5                     
        191 Perkins                         2500     2887.5                     
        192 Bell                            4000       4620                     
        193 Everett                         3900     4504.5                     
        194 McCain                          3200       3696                     
        195 Jones                           2800       3234                     
        196 Walsh                           3100     3580.5                     
        197 Feeney                          3000       3465                     
        198 OConnell                        2600       3003                     

EMPLOYEE_ID LAST_NAME                     SALARY NEW_SALARY                     
----------- ------------------------- ---------- ----------                     
        199 Grant                           2600       3003                     
        200 Whalen                          4400       5082                     
        201 Hartstein                      13000      15015                     
        202 Fay                             6000       6930                     
        203 Mavris                          6500     7507.5                     
        204 Baer                           10000      11550                     
        205 Higgins                        12008   13869.24                     
        206 Gietz                           8300     9586.5                     

107 rows selected.

SQL> SELECT EMPLOYEE_ID, LAST_NAME, SALARY,TRUNC(SALARY*(115.5/100)) AS "NEW_SALARY"
  2  FROM EMPLOYEES;

EMPLOYEE_ID LAST_NAME                     SALARY NEW_SALARY                     
----------- ------------------------- ---------- ----------                     
        100 King                           24000      27720                     
        101 Kochhar                        17000      19635                     
        102 De Haan                        17000      19635                     
        103 Hunold                          9000      10395                     
        104 Ernst                           6000       6930                     
        105 Austin                          4800       5544                     
        106 Pataballa                       4800       5544                     
        107 Lorentz                         4200       4851                     
        108 Greenberg                      12008      13869                     
        109 Faviet                          9000      10395                     
        110 Chen                            8200       9471                     

EMPLOYEE_ID LAST_NAME                     SALARY NEW_SALARY                     
----------- ------------------------- ---------- ----------                     
        111 Sciarra                         7700       8893                     
        112 Urman                           7800       9009                     
        113 Popp                            6900       7969                     
        114 Raphaely                       11000      12705                     
        115 Khoo                            3100       3580                     
        116 Baida                           2900       3349                     
        117 Tobias                          2800       3234                     
        118 Himuro                          2600       3003                     
        119 Colmenares                      2500       2887                     
        120 Weiss                           8000       9240                     
        121 Fripp                           8200       9471                     

EMPLOYEE_ID LAST_NAME                     SALARY NEW_SALARY                     
----------- ------------------------- ---------- ----------                     
        122 Kaufling                        7900       9124                     
        123 Vollman                         6500       7507                     
        124 Mourgos                         5800       6699                     
        125 Nayer                           3200       3696                     
        126 Mikkilineni                     2700       3118                     
        127 Landry                          2400       2772                     
        128 Markle                          2200       2541                     
        129 Bissot                          3300       3811                     
        130 Atkinson                        2800       3234                     
        131 Marlow                          2500       2887                     
        132 Olson                           2100       2425                     

EMPLOYEE_ID LAST_NAME                     SALARY NEW_SALARY                     
----------- ------------------------- ---------- ----------                     
        133 Mallin                          3300       3811                     
        134 Rogers                          2900       3349                     
        135 Gee                             2400       2772                     
        136 Philtanker                      2200       2541                     
        137 Ladwig                          3600       4158                     
        138 Stiles                          3200       3696                     
        139 Seo                             2700       3118                     
        140 Patel                           2500       2887                     
        141 Rajs                            3500       4042                     
        142 Davies                          3100       3580                     
        143 Matos                           2600       3003                     

EMPLOYEE_ID LAST_NAME                     SALARY NEW_SALARY                     
----------- ------------------------- ---------- ----------                     
        144 Vargas                          2500       2887                     
        145 Russell                        14000      16170                     
        146 Partners                       13500      15592                     
        147 Errazuriz                      12000      13860                     
        148 Cambrault                      11000      12705                     
        149 Zlotkey                        10500      12127                     
        150 Tucker                         10000      11550                     
        151 Bernstein                       9500      10972                     
        152 Hall                            9000      10395                     
        153 Olsen                           8000       9240                     
        154 Cambrault                       7500       8662                     

EMPLOYEE_ID LAST_NAME                     SALARY NEW_SALARY                     
----------- ------------------------- ---------- ----------                     
        155 Tuvault                         7000       8085                     
        156 King                           10000      11550                     
        157 Sully                           9500      10972                     
        158 McEwen                          9000      10395                     
        159 Smith                           8000       9240                     
        160 Doran                           7500       8662                     
        161 Sewall                          7000       8085                     
        162 Vishney                        10500      12127                     
        163 Greene                          9500      10972                     
        164 Marvins                         7200       8316                     
        165 Lee                             6800       7854                     

EMPLOYEE_ID LAST_NAME                     SALARY NEW_SALARY                     
----------- ------------------------- ---------- ----------                     
        166 Ande                            6400       7392                     
        167 Banda                           6200       7161                     
        168 Ozer                           11500      13282                     
        169 Bloom                          10000      11550                     
        170 Fox                             9600      11088                     
        171 Smith                           7400       8547                     
        172 Bates                           7300       8431                     
        173 Kumar                           6100       7045                     
        174 Abel                           11000      12705                     
        175 Hutton                          8800      10164                     
        176 Taylor                          8600       9933                     

EMPLOYEE_ID LAST_NAME                     SALARY NEW_SALARY                     
----------- ------------------------- ---------- ----------                     
        177 Livingston                      8400       9702                     
        178 Grant                           7000       8085                     
        179 Johnson                         6200       7161                     
        180 Taylor                          3200       3696                     
        181 Fleaur                          3100       3580                     
        182 Sullivan                        2500       2887                     
        183 Geoni                           2800       3234                     
        184 Sarchand                        4200       4851                     
        185 Bull                            4100       4735                     
        186 Dellinger                       3400       3927                     
        187 Cabrio                          3000       3465                     

EMPLOYEE_ID LAST_NAME                     SALARY NEW_SALARY                     
----------- ------------------------- ---------- ----------                     
        188 Chung                           3800       4389                     
        189 Dilly                           3600       4158                     
        190 Gates                           2900       3349                     
        191 Perkins                         2500       2887                     
        192 Bell                            4000       4620                     
        193 Everett                         3900       4504                     
        194 McCain                          3200       3696                     
        195 Jones                           2800       3234                     
        196 Walsh                           3100       3580                     
        197 Feeney                          3000       3465                     
        198 OConnell                        2600       3003                     

EMPLOYEE_ID LAST_NAME                     SALARY NEW_SALARY                     
----------- ------------------------- ---------- ----------                     
        199 Grant                           2600       3003                     
        200 Whalen                          4400       5082                     
        201 Hartstein                      13000      15015                     
        202 Fay                             6000       6930                     
        203 Mavris                          6500       7507                     
        204 Baer                           10000      11550                     
        205 Higgins                        12008      13869                     
        206 Gietz                           8300       9586                     

107 rows selected.

SQL> SELECT EMPLOYEE_ID, LAST_NAME, SALARY, (TRUNC(SALARY*(115.5/100))) AS "NEW_SALARY", ((TRUNC(SALARY*(115.5/100)))-SALARY) AS "INCREASE"
  2  FROM EMPLOYEES;

EMPLOYEE_ID LAST_NAME                     SALARY NEW_SALARY   INCREASE          
----------- ------------------------- ---------- ---------- ----------          
        100 King                           24000      27720       3720          
        101 Kochhar                        17000      19635       2635          
        102 De Haan                        17000      19635       2635          
        103 Hunold                          9000      10395       1395          
        104 Ernst                           6000       6930        930          
        105 Austin                          4800       5544        744          
        106 Pataballa                       4800       5544        744          
        107 Lorentz                         4200       4851        651          
        108 Greenberg                      12008      13869       1861          
        109 Faviet                          9000      10395       1395          
        110 Chen                            8200       9471       1271          

EMPLOYEE_ID LAST_NAME                     SALARY NEW_SALARY   INCREASE          
----------- ------------------------- ---------- ---------- ----------          
        111 Sciarra                         7700       8893       1193          
        112 Urman                           7800       9009       1209          
        113 Popp                            6900       7969       1069          
        114 Raphaely                       11000      12705       1705          
        115 Khoo                            3100       3580        480          
        116 Baida                           2900       3349        449          
        117 Tobias                          2800       3234        434          
        118 Himuro                          2600       3003        403          
        119 Colmenares                      2500       2887        387          
        120 Weiss                           8000       9240       1240          
        121 Fripp                           8200       9471       1271          

EMPLOYEE_ID LAST_NAME                     SALARY NEW_SALARY   INCREASE          
----------- ------------------------- ---------- ---------- ----------          
        122 Kaufling                        7900       9124       1224          
        123 Vollman                         6500       7507       1007          
        124 Mourgos                         5800       6699        899          
        125 Nayer                           3200       3696        496          
        126 Mikkilineni                     2700       3118        418          
        127 Landry                          2400       2772        372          
        128 Markle                          2200       2541        341          
        129 Bissot                          3300       3811        511          
        130 Atkinson                        2800       3234        434          
        131 Marlow                          2500       2887        387          
        132 Olson                           2100       2425        325          

EMPLOYEE_ID LAST_NAME                     SALARY NEW_SALARY   INCREASE          
----------- ------------------------- ---------- ---------- ----------          
        133 Mallin                          3300       3811        511          
        134 Rogers                          2900       3349        449          
        135 Gee                             2400       2772        372          
        136 Philtanker                      2200       2541        341          
        137 Ladwig                          3600       4158        558          
        138 Stiles                          3200       3696        496          
        139 Seo                             2700       3118        418          
        140 Patel                           2500       2887        387          
        141 Rajs                            3500       4042        542          
        142 Davies                          3100       3580        480          
        143 Matos                           2600       3003        403          

EMPLOYEE_ID LAST_NAME                     SALARY NEW_SALARY   INCREASE          
----------- ------------------------- ---------- ---------- ----------          
        144 Vargas                          2500       2887        387          
        145 Russell                        14000      16170       2170          
        146 Partners                       13500      15592       2092          
        147 Errazuriz                      12000      13860       1860          
        148 Cambrault                      11000      12705       1705          
        149 Zlotkey                        10500      12127       1627          
        150 Tucker                         10000      11550       1550          
        151 Bernstein                       9500      10972       1472          
        152 Hall                            9000      10395       1395          
        153 Olsen                           8000       9240       1240          
        154 Cambrault                       7500       8662       1162          

EMPLOYEE_ID LAST_NAME                     SALARY NEW_SALARY   INCREASE          
----------- ------------------------- ---------- ---------- ----------          
        155 Tuvault                         7000       8085       1085          
        156 King                           10000      11550       1550          
        157 Sully                           9500      10972       1472          
        158 McEwen                          9000      10395       1395          
        159 Smith                           8000       9240       1240          
        160 Doran                           7500       8662       1162          
        161 Sewall                          7000       8085       1085          
        162 Vishney                        10500      12127       1627          
        163 Greene                          9500      10972       1472          
        164 Marvins                         7200       8316       1116          
        165 Lee                             6800       7854       1054          

EMPLOYEE_ID LAST_NAME                     SALARY NEW_SALARY   INCREASE          
----------- ------------------------- ---------- ---------- ----------          
        166 Ande                            6400       7392        992          
        167 Banda                           6200       7161        961          
        168 Ozer                           11500      13282       1782          
        169 Bloom                          10000      11550       1550          
        170 Fox                             9600      11088       1488          
        171 Smith                           7400       8547       1147          
        172 Bates                           7300       8431       1131          
        173 Kumar                           6100       7045        945          
        174 Abel                           11000      12705       1705          
        175 Hutton                          8800      10164       1364          
        176 Taylor                          8600       9933       1333          

EMPLOYEE_ID LAST_NAME                     SALARY NEW_SALARY   INCREASE          
----------- ------------------------- ---------- ---------- ----------          
        177 Livingston                      8400       9702       1302          
        178 Grant                           7000       8085       1085          
        179 Johnson                         6200       7161        961          
        180 Taylor                          3200       3696        496          
        181 Fleaur                          3100       3580        480          
        182 Sullivan                        2500       2887        387          
        183 Geoni                           2800       3234        434          
        184 Sarchand                        4200       4851        651          
        185 Bull                            4100       4735        635          
        186 Dellinger                       3400       3927        527          
        187 Cabrio                          3000       3465        465          

EMPLOYEE_ID LAST_NAME                     SALARY NEW_SALARY   INCREASE          
----------- ------------------------- ---------- ---------- ----------          
        188 Chung                           3800       4389        589          
        189 Dilly                           3600       4158        558          
        190 Gates                           2900       3349        449          
        191 Perkins                         2500       2887        387          
        192 Bell                            4000       4620        620          
        193 Everett                         3900       4504        604          
        194 McCain                          3200       3696        496          
        195 Jones                           2800       3234        434          
        196 Walsh                           3100       3580        480          
        197 Feeney                          3000       3465        465          
        198 OConnell                        2600       3003        403          

EMPLOYEE_ID LAST_NAME                     SALARY NEW_SALARY   INCREASE          
----------- ------------------------- ---------- ---------- ----------          
        199 Grant                           2600       3003        403          
        200 Whalen                          4400       5082        682          
        201 Hartstein                      13000      15015       2015          
        202 Fay                             6000       6930        930          
        203 Mavris                          6500       7507       1007          
        204 Baer                           10000      11550       1550          
        205 Higgins                        12008      13869       1861          
        206 Gietz                           8300       9586       1286          

107 rows selected.

SQL> SELECT INITCAP(LAST_NAME), LENGTH(LAST_NAME)
  2  FROM EMPLOYEES
  3  WHERE LAST_NAME LIKE 'J%' OR LAST_NAME LIKE 'A%' OR LAST_NAME LIKE 'M%';

INITCAP(LAST_NAME)        LENGTH(LAST_NAME)                                     
------------------------- -----------------                                     
Abel                                      4                                     
Ande                                      4                                     
Atkinson                                  8                                     
Austin                                    6                                     
Johnson                                   7                                     
Jones                                     5                                     
Mallin                                    6                                     
Markle                                    6                                     
Marlow                                    6                                     
Marvins                                   7                                     
Matos                                     5                                     

INITCAP(LAST_NAME)        LENGTH(LAST_NAME)                                     
------------------------- -----------------                                     
Mavris                                    6                                     
Mccain                                    6                                     
Mcewen                                    6                                     
Mikkilineni                              11                                     
Mourgos                                   7                                     

16 rows selected.

SQL> SELECT LAST_NAME, (ROUND((SYSDATE-HIRE_DATE)*12)) AS "MONTHS_WORKED"
  2  FROM EMPLOYEES;

LAST_NAME                 MONTHS_WORKED                                         
------------------------- -------------                                         
King                              72450                                         
Kochhar                           62526                                         
De Haan                           83070                                         
Hunold                            61278                                         
Ernst                             55242                                         
Austin                            63582                                         
Pataballa                         60882                                         
Lorentz                           56478                                         
Greenberg                         76098                                         
Faviet                            76110                                         
Chen                              62442                                         

LAST_NAME                 MONTHS_WORKED                                         
------------------------- -------------                                         
Sciarra                           62418                                         
Urman                             60522                                         
Popp                              52842                                         
Raphaely                          74754                                         
Khoo                              72810                                         
Baida                             61398                                         
Tobias                            63234                                         
Himuro                            57486                                         
Colmenares                        54270                                         
Weiss                             67686                                         
Fripp                             64494                                         

LAST_NAME                 MONTHS_WORKED                                         
------------------------- -------------                                         
Kaufling                          73014                                         
Vollman                           62298                                         
Mourgos                           53094                                         
Nayer                             63330                                         
Mikkilineni                       58062                                         
Landry                            56766                                         
Markle                            51738                                         
Bissot                            62910                                         
Atkinson                          62058                                         
Marlow                            65130                                         
Olson                             55734                                         

LAST_NAME                 MONTHS_WORKED                                         
------------------------- -------------                                         
Mallin                            68094                                         
Rogers                            58458                                         
Gee                               52782                                         
Philtanker                        52110                                         
Ladwig                            72126                                         
Stiles                            62106                                         
Seo                               60798                                         
Patel                             60162                                         
Rajs                              70986                                         
Davies                            65346                                         
Matos                             60426                                         

LAST_NAME                 MONTHS_WORKED                                         
------------------------- -------------                                         
Vargas                            59034                                         
Russell                           66786                                         
Partners                          65634                                         
Errazuriz                         64866                                         
Cambrault                         53478                                         
Zlotkey                           52206                                         
Tucker                            65334                                         
Bernstein                         64698                                         
Hall                              62910                                         
Olsen                             60246                                         
Cambrault                         57198                                         

LAST_NAME                 MONTHS_WORKED                                         
------------------------- -------------                                         
Tuvault                           53010                                         
King                              69726                                         
Sully                             69318                                         
McEwen                            67518                                         
Smith                             64866                                         
Doran                             61506                                         
Sewall                            57630                                         
Vishney                           61914                                         
Greene                            55998                                         
Marvins                           52266                                         
Lee                               51906                                         

LAST_NAME                 MONTHS_WORKED                                         
------------------------- -------------                                         
Ande                              51546                                         
Banda                             51210                                         
Ozer                              64854                                         
Bloom                             60330                                         
Fox                               61026                                         
Smith                             56286                                         
Bates                             55938                                         
Kumar                             51210                                         
Abel                              68502                                         
Hutton                            64758                                         
Taylor                            60318                                         

LAST_NAME                 MONTHS_WORKED                                         
------------------------- -------------                                         
Livingston                        59958                                         
Grant                             55206                                         
Johnson                           52506                                         
Taylor                            61026                                         
Fleaur                            60666                                         
Sullivan                          54870                                         
Geoni                             52146                                         
Sarchand                          69762                                         
Bull                              65082                                         
Dellinger                         59214                                         
Cabrio                            56478                                         

LAST_NAME                 MONTHS_WORKED                                         
------------------------- -------------                                         
Chung                             63714                                         
Dilly                             62994                                         
Gates                             59010                                         
Perkins                           52698                                         
Bell                              69666                                         
Everett                           64950                                         
McCain                            59130                                         
Jones                             56022                                         
Walsh                             59946                                         
Feeney                            59598                                         
OConnell                          54870                                         

LAST_NAME                 MONTHS_WORKED                                         
------------------------- -------------                                         
Grant                             52398                                         
Whalen                            71346                                         
Hartstein                         69510                                         
Fay                               62946                                         
Mavris                            76950                                         
Baer                              76950                                         
Higgins                           76950                                         
Gietz                             76950                                         

107 rows selected.

SQL> SELECT LAST_NAME, (ROUND((SYSDATE-HIRE_DATE)/12)) AS "MONTHS_WORKED"
  2  FROM EMPLOYEES;

LAST_NAME                 MONTHS_WORKED                                         
------------------------- -------------                                         
King                                503                                         
Kochhar                             434                                         
De Haan                             577                                         
Hunold                              426                                         
Ernst                               384                                         
Austin                              442                                         
Pataballa                           423                                         
Lorentz                             392                                         
Greenberg                           528                                         
Faviet                              529                                         
Chen                                434                                         

LAST_NAME                 MONTHS_WORKED                                         
------------------------- -------------                                         
Sciarra                             433                                         
Urman                               420                                         
Popp                                367                                         
Raphaely                            519                                         
Khoo                                506                                         
Baida                               426                                         
Tobias                              439                                         
Himuro                              399                                         
Colmenares                          377                                         
Weiss                               470                                         
Fripp                               448                                         

LAST_NAME                 MONTHS_WORKED                                         
------------------------- -------------                                         
Kaufling                            507                                         
Vollman                             433                                         
Mourgos                             369                                         
Nayer                               440                                         
Mikkilineni                         403                                         
Landry                              394                                         
Markle                              359                                         
Bissot                              437                                         
Atkinson                            431                                         
Marlow                              452                                         
Olson                               387                                         

LAST_NAME                 MONTHS_WORKED                                         
------------------------- -------------                                         
Mallin                              473                                         
Rogers                              406                                         
Gee                                 367                                         
Philtanker                          362                                         
Ladwig                              501                                         
Stiles                              431                                         
Seo                                 422                                         
Patel                               418                                         
Rajs                                493                                         
Davies                              454                                         
Matos                               420                                         

LAST_NAME                 MONTHS_WORKED                                         
------------------------- -------------                                         
Vargas                              410                                         
Russell                             464                                         
Partners                            456                                         
Errazuriz                           450                                         
Cambrault                           371                                         
Zlotkey                             363                                         
Tucker                              454                                         
Bernstein                           449                                         
Hall                                437                                         
Olsen                               418                                         
Cambrault                           397                                         

LAST_NAME                 MONTHS_WORKED                                         
------------------------- -------------                                         
Tuvault                             368                                         
King                                484                                         
Sully                               481                                         
McEwen                              469                                         
Smith                               450                                         
Doran                               427                                         
Sewall                              400                                         
Vishney                             430                                         
Greene                              389                                         
Marvins                             363                                         
Lee                                 360                                         

LAST_NAME                 MONTHS_WORKED                                         
------------------------- -------------                                         
Ande                                358                                         
Banda                               356                                         
Ozer                                450                                         
Bloom                               419                                         
Fox                                 424                                         
Smith                               391                                         
Bates                               388                                         
Kumar                               356                                         
Abel                                476                                         
Hutton                              450                                         
Taylor                              419                                         

LAST_NAME                 MONTHS_WORKED                                         
------------------------- -------------                                         
Livingston                          416                                         
Grant                               383                                         
Johnson                             365                                         
Taylor                              424                                         
Fleaur                              421                                         
Sullivan                            381                                         
Geoni                               362                                         
Sarchand                            484                                         
Bull                                452                                         
Dellinger                           411                                         
Cabrio                              392                                         

LAST_NAME                 MONTHS_WORKED                                         
------------------------- -------------                                         
Chung                               442                                         
Dilly                               437                                         
Gates                               410                                         
Perkins                             366                                         
Bell                                484                                         
Everett                             451                                         
McCain                              411                                         
Jones                               389                                         
Walsh                               416                                         
Feeney                              414                                         
OConnell                            381                                         

LAST_NAME                 MONTHS_WORKED                                         
------------------------- -------------                                         
Grant                               364                                         
Whalen                              495                                         
Hartstein                           483                                         
Fay                                 437                                         
Mavris                              534                                         
Baer                                534                                         
Higgins                             534                                         
Gietz                               534                                         

107 rows selected.

SQL> FROM EMPLOYEES;
SP2-0734: unknown command beginning "FROM EMPLO..." - rest of line ignored.
SQL> 
SQL> SELECT LAST_NAME, LPAD(SALARY,15,$) "SALARY"
  2  FROM EMPLOYEES;
SELECT LAST_NAME, LPAD(SALARY,15,$) "SALARY"
                                 *
ERROR at line 1:
ORA-00911: invalid character 


SQL> SELECT LAST_NAME, LPAD(SALARY,15,'$') "SALARY"
  2  FROM EMPLOYEES;

LAST_NAME                 SALARY                                                
------------------------- ---------------                                       
King                      $$$$$$$$$$24000                                       
Kochhar                   $$$$$$$$$$17000                                       
De Haan                   $$$$$$$$$$17000                                       
Hunold                    $$$$$$$$$$$9000                                       
Ernst                     $$$$$$$$$$$6000                                       
Austin                    $$$$$$$$$$$4800                                       
Pataballa                 $$$$$$$$$$$4800                                       
Lorentz                   $$$$$$$$$$$4200                                       
Greenberg                 $$$$$$$$$$12008                                       
Faviet                    $$$$$$$$$$$9000                                       
Chen                      $$$$$$$$$$$8200                                       

LAST_NAME                 SALARY                                                
------------------------- ---------------                                       
Sciarra                   $$$$$$$$$$$7700                                       
Urman                     $$$$$$$$$$$7800                                       
Popp                      $$$$$$$$$$$6900                                       
Raphaely                  $$$$$$$$$$11000                                       
Khoo                      $$$$$$$$$$$3100                                       
Baida                     $$$$$$$$$$$2900                                       
Tobias                    $$$$$$$$$$$2800                                       
Himuro                    $$$$$$$$$$$2600                                       
Colmenares                $$$$$$$$$$$2500                                       
Weiss                     $$$$$$$$$$$8000                                       
Fripp                     $$$$$$$$$$$8200                                       

LAST_NAME                 SALARY                                                
------------------------- ---------------                                       
Kaufling                  $$$$$$$$$$$7900                                       
Vollman                   $$$$$$$$$$$6500                                       
Mourgos                   $$$$$$$$$$$5800                                       
Nayer                     $$$$$$$$$$$3200                                       
Mikkilineni               $$$$$$$$$$$2700                                       
Landry                    $$$$$$$$$$$2400                                       
Markle                    $$$$$$$$$$$2200                                       
Bissot                    $$$$$$$$$$$3300                                       
Atkinson                  $$$$$$$$$$$2800                                       
Marlow                    $$$$$$$$$$$2500                                       
Olson                     $$$$$$$$$$$2100                                       

LAST_NAME                 SALARY                                                
------------------------- ---------------                                       
Mallin                    $$$$$$$$$$$3300                                       
Rogers                    $$$$$$$$$$$2900                                       
Gee                       $$$$$$$$$$$2400                                       
Philtanker                $$$$$$$$$$$2200                                       
Ladwig                    $$$$$$$$$$$3600                                       
Stiles                    $$$$$$$$$$$3200                                       
Seo                       $$$$$$$$$$$2700                                       
Patel                     $$$$$$$$$$$2500                                       
Rajs                      $$$$$$$$$$$3500                                       
Davies                    $$$$$$$$$$$3100                                       
Matos                     $$$$$$$$$$$2600                                       

LAST_NAME                 SALARY                                                
------------------------- ---------------                                       
Vargas                    $$$$$$$$$$$2500                                       
Russell                   $$$$$$$$$$14000                                       
Partners                  $$$$$$$$$$13500                                       
Errazuriz                 $$$$$$$$$$12000                                       
Cambrault                 $$$$$$$$$$11000                                       
Zlotkey                   $$$$$$$$$$10500                                       
Tucker                    $$$$$$$$$$10000                                       
Bernstein                 $$$$$$$$$$$9500                                       
Hall                      $$$$$$$$$$$9000                                       
Olsen                     $$$$$$$$$$$8000                                       
Cambrault                 $$$$$$$$$$$7500                                       

LAST_NAME                 SALARY                                                
------------------------- ---------------                                       
Tuvault                   $$$$$$$$$$$7000                                       
King                      $$$$$$$$$$10000                                       
Sully                     $$$$$$$$$$$9500                                       
McEwen                    $$$$$$$$$$$9000                                       
Smith                     $$$$$$$$$$$8000                                       
Doran                     $$$$$$$$$$$7500                                       
Sewall                    $$$$$$$$$$$7000                                       
Vishney                   $$$$$$$$$$10500                                       
Greene                    $$$$$$$$$$$9500                                       
Marvins                   $$$$$$$$$$$7200                                       
Lee                       $$$$$$$$$$$6800                                       

LAST_NAME                 SALARY                                                
------------------------- ---------------                                       
Ande                      $$$$$$$$$$$6400                                       
Banda                     $$$$$$$$$$$6200                                       
Ozer                      $$$$$$$$$$11500                                       
Bloom                     $$$$$$$$$$10000                                       
Fox                       $$$$$$$$$$$9600                                       
Smith                     $$$$$$$$$$$7400                                       
Bates                     $$$$$$$$$$$7300                                       
Kumar                     $$$$$$$$$$$6100                                       
Abel                      $$$$$$$$$$11000                                       
Hutton                    $$$$$$$$$$$8800                                       
Taylor                    $$$$$$$$$$$8600                                       

LAST_NAME                 SALARY                                                
------------------------- ---------------                                       
Livingston                $$$$$$$$$$$8400                                       
Grant                     $$$$$$$$$$$7000                                       
Johnson                   $$$$$$$$$$$6200                                       
Taylor                    $$$$$$$$$$$3200                                       
Fleaur                    $$$$$$$$$$$3100                                       
Sullivan                  $$$$$$$$$$$2500                                       
Geoni                     $$$$$$$$$$$2800                                       
Sarchand                  $$$$$$$$$$$4200                                       
Bull                      $$$$$$$$$$$4100                                       
Dellinger                 $$$$$$$$$$$3400                                       
Cabrio                    $$$$$$$$$$$3000                                       

LAST_NAME                 SALARY                                                
------------------------- ---------------                                       
Chung                     $$$$$$$$$$$3800                                       
Dilly                     $$$$$$$$$$$3600                                       
Gates                     $$$$$$$$$$$2900                                       
Perkins                   $$$$$$$$$$$2500                                       
Bell                      $$$$$$$$$$$4000                                       
Everett                   $$$$$$$$$$$3900                                       
McCain                    $$$$$$$$$$$3200                                       
Jones                     $$$$$$$$$$$2800                                       
Walsh                     $$$$$$$$$$$3100                                       
Feeney                    $$$$$$$$$$$3000                                       
OConnell                  $$$$$$$$$$$2600                                       

LAST_NAME                 SALARY                                                
------------------------- ---------------                                       
Grant                     $$$$$$$$$$$2600                                       
Whalen                    $$$$$$$$$$$4400                                       
Hartstein                 $$$$$$$$$$13000                                       
Fay                       $$$$$$$$$$$6000                                       
Mavris                    $$$$$$$$$$$6500                                       
Baer                      $$$$$$$$$$10000                                       
Higgins                   $$$$$$$$$$12008                                       
Gietz                     $$$$$$$$$$$8300                                       

107 rows selected.

SQL> SELECT RPAD(LAST_NAME,8)||' '||RPAD(SALARY/1000,'*')
  2  FROM EMPLOYEES;
SELECT RPAD(LAST_NAME,8)||' '||RPAD(SALARY/1000,'*')
                                                *
ERROR at line 1:
ORA-01722: invalid number 


SQL> SELECT RPAD(LAST_NAME,8)||' '||RPAD(SALARY/1000+1,'*')
  2  FROM EMPLOYEES;
SELECT RPAD(LAST_NAME,8)||' '||RPAD(SALARY/1000+1,'*')
                                                  *
ERROR at line 1:
ORA-01722: invalid number 


SQL> SELECT RPAD(LAST_NAME,8)||' '||RPAD(' ',(SALARY/1000+1),'*')
  2  FROM EMPLOYEES;

RPAD(LAST_NAME,8)||''||RPAD('',(SALARY/1000+1),'*')                             
--------------------------------------------------------------------------------
King      ************************                                              
Kochhar   *****************                                                     
De Haan   *****************                                                     
Hunold    *********                                                             
Ernst     ******                                                                
Austin    ****                                                                  
Pataball  ****                                                                  
Lorentz   ****                                                                  
Greenber  ************                                                          
Faviet    *********                                                             
Chen      ********                                                              

RPAD(LAST_NAME,8)||''||RPAD('',(SALARY/1000+1),'*')                             
--------------------------------------------------------------------------------
Sciarra   *******                                                               
Urman     *******                                                               
Popp      ******                                                                
Raphaely  ***********                                                           
Khoo      ***                                                                   
Baida     **                                                                    
Tobias    **                                                                    
Himuro    **                                                                    
Colmenar  **                                                                    
Weiss     ********                                                              
Fripp     ********                                                              

RPAD(LAST_NAME,8)||''||RPAD('',(SALARY/1000+1),'*')                             
--------------------------------------------------------------------------------
Kaufling  *******                                                               
Vollman   ******                                                                
Mourgos   *****                                                                 
Nayer     ***                                                                   
Mikkilin  **                                                                    
Landry    **                                                                    
Markle    **                                                                    
Bissot    ***                                                                   
Atkinson  **                                                                    
Marlow    **                                                                    
Olson     **                                                                    

RPAD(LAST_NAME,8)||''||RPAD('',(SALARY/1000+1),'*')                             
--------------------------------------------------------------------------------
Mallin    ***                                                                   
Rogers    **                                                                    
Gee       **                                                                    
Philtank  **                                                                    
Ladwig    ***                                                                   
Stiles    ***                                                                   
Seo       **                                                                    
Patel     **                                                                    
Rajs      ***                                                                   
Davies    ***                                                                   
Matos     **                                                                    

RPAD(LAST_NAME,8)||''||RPAD('',(SALARY/1000+1),'*')                             
--------------------------------------------------------------------------------
Vargas    **                                                                    
Russell   **************                                                        
Partners  *************                                                         
Errazuri  ************                                                          
Cambraul  ***********                                                           
Zlotkey   **********                                                            
Tucker    **********                                                            
Bernstei  *********                                                             
Hall      *********                                                             
Olsen     ********                                                              
Cambraul  *******                                                               

RPAD(LAST_NAME,8)||''||RPAD('',(SALARY/1000+1),'*')                             
--------------------------------------------------------------------------------
Tuvault   *******                                                               
King      **********                                                            
Sully     *********                                                             
McEwen    *********                                                             
Smith     ********                                                              
Doran     *******                                                               
Sewall    *******                                                               
Vishney   **********                                                            
Greene    *********                                                             
Marvins   *******                                                               
Lee       ******                                                                

RPAD(LAST_NAME,8)||''||RPAD('',(SALARY/1000+1),'*')                             
--------------------------------------------------------------------------------
Ande      ******                                                                
Banda     ******                                                                
Ozer      ***********                                                           
Bloom     **********                                                            
Fox       *********                                                             
Smith     *******                                                               
Bates     *******                                                               
Kumar     ******                                                                
Abel      ***********                                                           
Hutton    ********                                                              
Taylor    ********                                                              

RPAD(LAST_NAME,8)||''||RPAD('',(SALARY/1000+1),'*')                             
--------------------------------------------------------------------------------
Livingst  ********                                                              
Grant     *******                                                               
Johnson   ******                                                                
Taylor    ***                                                                   
Fleaur    ***                                                                   
Sullivan  **                                                                    
Geoni     **                                                                    
Sarchand  ****                                                                  
Bull      ****                                                                  
Dellinge  ***                                                                   
Cabrio    ***                                                                   

RPAD(LAST_NAME,8)||''||RPAD('',(SALARY/1000+1),'*')                             
--------------------------------------------------------------------------------
Chung     ***                                                                   
Dilly     ***                                                                   
Gates     **                                                                    
Perkins   **                                                                    
Bell      ****                                                                  
Everett   ***                                                                   
McCain    ***                                                                   
Jones     **                                                                    
Walsh     ***                                                                   
Feeney    ***                                                                   
OConnell  **                                                                    

RPAD(LAST_NAME,8)||''||RPAD('',(SALARY/1000+1),'*')                             
--------------------------------------------------------------------------------
Grant     **                                                                    
Whalen    ****                                                                  
Hartstei  *************                                                         
Fay       ******                                                                
Mavris    ******                                                                
Baer      **********                                                            
Higgins   ************                                                          
Gietz     ********                                                              

107 rows selected.

SQL> SELECT RPAD(LAST_NAME,8)||' '||RPAD((SALARY/1000),'*')
  2  FROM EMPLOYEES;
SELECT RPAD(LAST_NAME,8)||' '||RPAD((SALARY/1000),'*')
                                                  *
ERROR at line 1:
ORA-01722: invalid number 


SQL> SELECT RPAD(LAST_NAME,8)||' '||RPAD(' ',(SALARY/1000),'*')
  2  FROM EMPLOYEES;

RPAD(LAST_NAME,8)||''||RPAD('',(SALARY/1000),'*')                               
--------------------------------------------------------------------------------
King      ***********************                                               
Kochhar   ****************                                                      
De Haan   ****************                                                      
Hunold    ********                                                              
Ernst     *****                                                                 
Austin    ***                                                                   
Pataball  ***                                                                   
Lorentz   ***                                                                   
Greenber  ***********                                                           
Faviet    ********                                                              
Chen      *******                                                               

RPAD(LAST_NAME,8)||''||RPAD('',(SALARY/1000),'*')                               
--------------------------------------------------------------------------------
Sciarra   ******                                                                
Urman     ******                                                                
Popp      *****                                                                 
Raphaely  **********                                                            
Khoo      **                                                                    
Baida     *                                                                     
Tobias    *                                                                     
Himuro    *                                                                     
Colmenar  *                                                                     
Weiss     *******                                                               
Fripp     *******                                                               

RPAD(LAST_NAME,8)||''||RPAD('',(SALARY/1000),'*')                               
--------------------------------------------------------------------------------
Kaufling  ******                                                                
Vollman   *****                                                                 
Mourgos   ****                                                                  
Nayer     **                                                                    
Mikkilin  *                                                                     
Landry    *                                                                     
Markle    *                                                                     
Bissot    **                                                                    
Atkinson  *                                                                     
Marlow    *                                                                     
Olson     *                                                                     

RPAD(LAST_NAME,8)||''||RPAD('',(SALARY/1000),'*')                               
--------------------------------------------------------------------------------
Mallin    **                                                                    
Rogers    *                                                                     
Gee       *                                                                     
Philtank  *                                                                     
Ladwig    **                                                                    
Stiles    **                                                                    
Seo       *                                                                     
Patel     *                                                                     
Rajs      **                                                                    
Davies    **                                                                    
Matos     *                                                                     

RPAD(LAST_NAME,8)||''||RPAD('',(SALARY/1000),'*')                               
--------------------------------------------------------------------------------
Vargas    *                                                                     
Russell   *************                                                         
Partners  ************                                                          
Errazuri  ***********                                                           
Cambraul  **********                                                            
Zlotkey   *********                                                             
Tucker    *********                                                             
Bernstei  ********                                                              
Hall      ********                                                              
Olsen     *******                                                               
Cambraul  ******                                                                

RPAD(LAST_NAME,8)||''||RPAD('',(SALARY/1000),'*')                               
--------------------------------------------------------------------------------
Tuvault   ******                                                                
King      *********                                                             
Sully     ********                                                              
McEwen    ********                                                              
Smith     *******                                                               
Doran     ******                                                                
Sewall    ******                                                                
Vishney   *********                                                             
Greene    ********                                                              
Marvins   ******                                                                
Lee       *****                                                                 

RPAD(LAST_NAME,8)||''||RPAD('',(SALARY/1000),'*')                               
--------------------------------------------------------------------------------
Ande      *****                                                                 
Banda     *****                                                                 
Ozer      **********                                                            
Bloom     *********                                                             
Fox       ********                                                              
Smith     ******                                                                
Bates     ******                                                                
Kumar     *****                                                                 
Abel      **********                                                            
Hutton    *******                                                               
Taylor    *******                                                               

RPAD(LAST_NAME,8)||''||RPAD('',(SALARY/1000),'*')                               
--------------------------------------------------------------------------------
Livingst  *******                                                               
Grant     ******                                                                
Johnson   *****                                                                 
Taylor    **                                                                    
Fleaur    **                                                                    
Sullivan  *                                                                     
Geoni     *                                                                     
Sarchand  ***                                                                   
Bull      ***                                                                   
Dellinge  **                                                                    
Cabrio    **                                                                    

RPAD(LAST_NAME,8)||''||RPAD('',(SALARY/1000),'*')                               
--------------------------------------------------------------------------------
Chung     **                                                                    
Dilly     **                                                                    
Gates     *                                                                     
Perkins   *                                                                     
Bell      ***                                                                   
Everett   **                                                                    
McCain    **                                                                    
Jones     *                                                                     
Walsh     **                                                                    
Feeney    **                                                                    
OConnell  *                                                                     

RPAD(LAST_NAME,8)||''||RPAD('',(SALARY/1000),'*')                               
--------------------------------------------------------------------------------
Grant     *                                                                     
Whalen    ***                                                                   
Hartstei  ************                                                          
Fay       *****                                                                 
Mavris    *****                                                                 
Baer      *********                                                             
Higgins   ***********                                                           
Gietz     *******                                                               

107 rows selected.

SQL> SELECT LAST_NAME, TRUNC((SYSDATE-HIRE_DATE)/7) TENURE
  2  FROM EMPLOYEES
  3  ORDER BY TRUNC((SYSDATE-HIRE_DATE)/7) DESC;

LAST_NAME                     TENURE                                            
------------------------- ----------                                            
De Haan                          988                                            
Gietz                            916                                            
Baer                             916                                            
Mavris                           916                                            
Higgins                          916                                            
Faviet                           906                                            
Greenberg                        905                                            
Raphaely                         889                                            
Kaufling                         869                                            
Khoo                             866                                            
King                             862                                            

LAST_NAME                     TENURE                                            
------------------------- ----------                                            
Ladwig                           858                                            
Whalen                           849                                            
Rajs                             845                                            
King                             830                                            
Sarchand                         830                                            
Bell                             829                                            
Hartstein                        827                                            
Sully                            825                                            
Abel                             815                                            
Mallin                           810                                            
Weiss                            805                                            

LAST_NAME                     TENURE                                            
------------------------- ----------                                            
McEwen                           803                                            
Russell                          795                                            
Partners                         781                                            
Tucker                           777                                            
Davies                           777                                            
Marlow                           775                                            
Bull                             774                                            
Everett                          773                                            
Smith                            772                                            
Errazuriz                        772                                            
Ozer                             772                                            

LAST_NAME                     TENURE                                            
------------------------- ----------                                            
Bernstein                        770                                            
Hutton                           770                                            
Fripp                            767                                            
Chung                            758                                            
Austin                           756                                            
Nayer                            753                                            
Tobias                           752                                            
Dilly                            749                                            
Fay                              749                                            
Hall                             748                                            
Bissot                           748                                            

LAST_NAME                     TENURE                                            
------------------------- ----------                                            
Kochhar                          744                                            
Chen                             743                                            
Sciarra                          743                                            
Vollman                          741                                            
Stiles                           739                                            
Atkinson                         738                                            
Vishney                          737                                            
Doran                            732                                            
Baida                            730                                            
Hunold                           729                                            
Fox                              726                                            

LAST_NAME                     TENURE                                            
------------------------- ----------                                            
Taylor                           726                                            
Pataballa                        724                                            
Seo                              723                                            
Fleaur                           722                                            
Urman                            720                                            
Matos                            719                                            
Bloom                            718                                            
Taylor                           718                                            
Olsen                            717                                            
Patel                            716                                            
Livingston                       713                                            

LAST_NAME                     TENURE                                            
------------------------- ----------                                            
Walsh                            713                                            
Feeney                           709                                            
Dellinger                        704                                            
McCain                           703                                            
Gates                            702                                            
Vargas                           702                                            
Rogers                           695                                            
Mikkilineni                      691                                            
Sewall                           686                                            
Himuro                           684                                            
Cambrault                        680                                            

LAST_NAME                     TENURE                                            
------------------------- ----------                                            
Landry                           675                                            
Lorentz                          672                                            
Cabrio                           672                                            
Smith                            670                                            
Greene                           666                                            
Jones                            666                                            
Bates                            665                                            
Olson                            663                                            
Ernst                            657                                            
Grant                            657                                            
OConnell                         653                                            

LAST_NAME                     TENURE                                            
------------------------- ----------                                            
Sullivan                         653                                            
Colmenares                       646                                            
Cambrault                        636                                            
Mourgos                          632                                            
Tuvault                          631                                            
Popp                             629                                            
Gee                              628                                            
Perkins                          627                                            
Johnson                          625                                            
Grant                            623                                            
Marvins                          622                                            

LAST_NAME                     TENURE                                            
------------------------- ----------                                            
Zlotkey                          621                                            
Geoni                            620                                            
Philtanker                       620                                            
Lee                              617                                            
Markle                           615                                            
Ande                             613                                            
Kumar                            609                                            
Banda                            609                                            

107 rows selected.

SQL> spool off
