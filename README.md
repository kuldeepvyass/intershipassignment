#assignment for internship
CREATE TABLE City (Id number,Name varchar2(17), Pincode varchar2(6), District varchar2(20), Population int );

INSERT INTO City VALUES ('2191','Kanpur',  133452,'Kanpur' , 5897890 );  
INSERT INTO City VALUES ('2192','Jaipur',  136752,  'Jaipur', 1897892 );  
INSERT INTO City VALUES ('2193','Patna',  135190,  'Patna', 5897893 );  
INSERT INTO City VALUES ('2194','Lucknow',  135112, 'Lucknow', 1897894 );  
INSERT INTO City VALUES ('2195','Delhi',  135113, 'Delhi', 5897895 );  
INSERT INTO City VALUES ('2197','Mumbai',  135114, 'Mumbai', 1897896 );  
INSERT INTO City VALUES ('2198','Banglore',  135115,'Banglore', 1897897 );  
INSERT INTO City VALUES ('2199','Hyderabad',  135116,'Hyderabad', 5897898 );  
INSERT INTO City VALUES ('2131','Haridwar',  135117,'Haridwar', 1897899 );  
SELECT Name FROM  City WHERE Population>5000000 ;



output: Kanpur
        Patna
        Delhi
        Hyderabad
