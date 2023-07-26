# DB CAR

| Column               | Type          | Attributes                 |
| -------------------- | ------------- | -------------------------- |
| id                   | BIGINT        | PRIMARY KEY AUTO_INCREMENT |
| brand                | VARCHAR(50)   | NOT NULL                   |
| model                | VARCHAR(50)   | NOT NULL                   |
| vin                  | VARCHAR(17)   | NOT NULL , UNIQUE          |
| immatricolation_year | YEAR          | NULL                       |
| kms                  | MEDIUMINT     | NOT NULL                   |
| license_plate        | VARCHAR(10)   | NULL                       |
| fuel                 | VARCHAR(30)   | NULL                       |
| color                | VARCHAR(30)   | NULL                       |
| photo                | VARCHAR       | NULL                       |
| video                | VARCHAR       | NULL                       |
| description          | TEXT          | NULL                       |
| cost                 | DECIMAL(10,2) | NOT NULL                   |
| price                | DECIMAL(10,2) | NULL                       |
| location             | VARCHAR(100)  | NULL                       |
