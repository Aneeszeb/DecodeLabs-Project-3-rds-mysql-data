# DecodeLabs Project-3 - AWS RDS MySQL with Data Collection

## Project Description
AWS RDS pe MySQL database instance create ki. 'decodelabs' database mein 'Interns' table bana ke sample data insert ki.

## Steps Performed
1. AWS RDS > Create database > MySQL engine select
2. Template: Free tier, DB identifier: decodelabs-db
3. Instance class: db.t3.micro, Region: eu-north-1 Stockholm
4. Security group mein Port 3306 open kiya
5. MySQL Workbench se RDS endpoint pe connect kiya
6. Database 'decodelabs' create ki
7. Table 'Interns' banai: InternID, FirstName, LastName, Email columns
8. Sample data insert ki: John Doe, Jane Smith, Anees Khan
9. SELECT * FROM Interns query run kar ke data verify kiya

## Screenshots
1. *RDS Creation - MySQL, db.t3.micro*  
   ![RDS Creation](WhatsApp%20Image%202026-06-19%20at%205.25.03%20PM%20%281%29.jpeg)

2. *RDS Available Status - decodelabs-db*  
   ![RDS Status](project%203.PNG)

3. *MySQL Workbench Connection Setup*  
   ![Workbench Connection](WhatsApp%20Image%202026-06-19%20at%205.25.03%20PM.jpeg)

4. *Data Collection - SELECT * FROM Interns Result Grid*  
   ![Data Result](WhatsApp%20Image%202026-06-19%20at%205.25.02%20PM.jpeg)

## AWS Resources Created
- *Service*: Amazon RDS MySQL
- *DB Identifier*: decodelabs-db
- *Database*: decodelabs
- *Table*: Interns
- *Engine*: MySQL Community 8.4.5
- *Instance Class*: db.t3.micro
- *Region*: eu-north-1
- *Endpoint*: decodelabs-db.clw8mq8s2u6w.eu-north-1.rds.amazonaws.com:3306

## Data Collected
| InternID | FirstName | LastName | Email |
| --- | --- | --- | --- |
| 1 | John | Doe | jdoe@decodelabs.com |
| 2 | Jane | Smith | jsmith@decodelabs.com |
| 3 | Anees | Khan | anees@decodelabs.com |

## Learnings
RDS managed service hai. MySQL Workbench se remote connect karke database manage ki. Security groups se access control important hai.
