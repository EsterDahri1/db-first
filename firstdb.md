## Title of my Table
Rental Car

## Columns
## Primary Key
id | TINYINT, NOTNULL, UNIQUE, AUTO_INCREMENT

## Non-key attributes
location | TINYINT(5), NULL
plate_id | VARCHAR(10), NULL, UNIQUE
color | VARCHAR(45), NOTNULL
brand | VARCHAR(45), NOTNULL
model | VARCHAR(45), NOTNULL
description | TEXT, NULL
registration_year | TIMESTAMP(YYYY-MM), NOTNULL
gearbox | VARCHAR(20), NOTNULL
fuel | VARCHAR(20), NOTNULL
mileage | MEDIUMINT (300000), NULL
price | MEDIUMINT (4000000), NOTNULL
availability | VARCHAR(3), NOTNULL