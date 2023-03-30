# postgresql
creating reading updating  and adding data to postgresql database
INSERT INTO regions (region-id,region-name)
VALUES(1,'Europe');
INSERT INTO regions (region-id,region-name)VALUES(2,'America');
INSERT INTO regions (region-id,region-name)VALUES(3,'Asia');
INSERT INTO regions (region-id,region-name)VALUES(4,' East and Africa');

INSERT INTO countries(country-id,country-name,region-id)VALUES('AR','ARGENTINA',2);
INSERT INTO countries(country-id,country-name,region-id)VALUES ('AU','Australia',3);
INSERT INTO countries(country-id,country-name,region-id)VALUES('BE','Belgium',1);
INSERT INTO countries(country-id,country-name,region-id)VALUES('BR','Brazil',2);
INSERT INTO countries(country-id,country-name,region-id)VALUES('CA','Canada',2);
INSERT INTO countries(country-id,country-name,region-id)VALUES ('CH','Switzerland',1);
INSERT INTO countries(country-id,country-name,region-id)VALUES ('CN','CHINA',3);
INSERT INTO countries(country-id,country-name,region-id)VALUES ('DE','GERMANY',1);
INSERT INTO countries(country-id,country-name,region-id)VALUES ('DK','DENMARK',1);
INSERT INTO countries(country-id,country-name,region-id)VALUES ('EG','EGYPT',4);
INSERT INTO countries(country-id,country-name,region-id)VALUES ('FR','FRANCE',1);
INSERT INTO countries(country-id,country-name,region-id)VALUES ('HK','HONG KONG',3);
INSERT INTO countries(country-id,country-name,region-id)VALUES ('IL','ISRAEL',4);
INSERT INTO countries(country-id,country-name,region-id)VALUES ('IN','INDIA',3);

INSERT INTO countries(country-id,country-name,region-id)VALUES ('TI','ITALY',1);
INSERT INTO countries(country-id,country-name,region-id)VALUES('JP','JAPAN',3);
INSERT INTO countries(country-id,country-name,region-id)VALUES ('KW','KUWAIT',4);
INSERT INTO countries(country-id,country-name,region-id)VALUES ('MX','MEXICO',2);
INSERT INTO countries(country-id,country-name,region-id)VALUES ('NG','NIGERIA',4);
INSERT INTO countries(country-id,country-name,region-id)VALUES ('NL','NETHERLANDS',1);
INSERT INTO countries(country-id,country-name,region-id)VALUES ('SG','SINGAPORE',3);
INSERT INTO countries(country-id,country-name,region-id)VALUES ('UK','UNITED KINGDOM',1);
INSERT INTO countries(country-id,country-name,region-id)VALUES ('US','UNITED STATES OF AMERICA',2);
INSERT INTO countries(country-id,country-name,region-id)VALUES ('ZM','ZAMBIA',4);
INSERT INTO countries(country-id,country-name,region-id)VALUES ('ZW','ZIMBABWE',4);

INSERT INTO locations(location-id,street-address, postal-code,city,States-province,country-id)
VALUES (1400,'2014 Jabberworky Rd','26192','South lake','Texas','US');
INSERT INTO locations(location-id,street-address, postal-code,city,States-province,country-id)VALUES (1500,'2011 Interiors Bivd','99236','South San Franscisco','California','US');
INSERT INTO locations(location-id,street-address, postal-code,city,States-province,country-id)VALUES (1700,'2004 Charade Rd','98199','Seattle','Washington','US');
