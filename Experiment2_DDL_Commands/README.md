# Experiment 2: DDL Commands

## AIM
To study and implement DDL commands and different types of constraints.

## THEORY

### 1. CREATE
Used to create a new relation (table).

**Syntax:**
```sql
CREATE TABLE (
  field_1 data_type(size),
  field_2 data_type(size),
  ...
);
```
### 2. ALTER
Used to add, modify, drop, or rename fields in an existing relation.
(a) ADD
```sql
ALTER TABLE std ADD (Address CHAR(10));
```
(b) MODIFY
```sql
ALTER TABLE relation_name MODIFY (field_1 new_data_type(size));
```
(c) DROP
```sql
ALTER TABLE relation_name DROP COLUMN field_name;
```
(d) RENAME
```sql
ALTER TABLE relation_name RENAME COLUMN old_field_name TO new_field_name;
```
### 3. DROP TABLE
Used to permanently delete the structure and data of a table.
```sql
DROP TABLE relation_name;
```
### 4. RENAME
Used to rename an existing database object.
```sql
RENAME TABLE old_relation_name TO new_relation_name;
```
### CONSTRAINTS
Constraints are used to specify rules for the data in a table. If there is any violation between the constraint and the data action, the action is aborted by the constraint. It can be specified when the table is created (using CREATE TABLE) or after it is created (using ALTER TABLE).
### 1. NOT NULL
When a column is defined as NOT NULL, it becomes mandatory to enter a value in that column.
Syntax:
```sql
CREATE TABLE Table_Name (
  column_name data_type(size) NOT NULL
);
```
### 2. UNIQUE
Ensures that values in a column are unique.
Syntax:
```sql
CREATE TABLE Table_Name (
  column_name data_type(size) UNIQUE
);
```
### 3. CHECK
Specifies a condition that each row must satisfy.
Syntax:
```sql
CREATE TABLE Table_Name (
  column_name data_type(size) CHECK (logical_expression)
);
```
### 4. PRIMARY KEY
Used to uniquely identify each record in a table.
Properties:
Must contain unique values.
Cannot be null.
Should contain minimal fields.
Syntax:
```sql
CREATE TABLE Table_Name (
  column_name data_type(size) PRIMARY KEY
);
```
### 5. FOREIGN KEY
Used to reference the primary key of another table.
Syntax:
```sql
CREATE TABLE Table_Name (
  column_name data_type(size),
  FOREIGN KEY (column_name) REFERENCES other_table(column)
);
```
### 6. DEFAULT
Used to insert a default value into a column if no value is specified.

Syntax:
```sql
CREATE TABLE Table_Name (
  col_name1 data_type,
  col_name2 data_type,
  col_name3 data_type DEFAULT 'default_value'
);
```

**Question 1**
--
-- <img width="1403" height="387" alt="image" src="https://github.com/user-attachments/assets/2b34de29-7368-478a-8463-8adf316b9d23" />




sql
<img width="824" height="223" alt="image" src="https://github.com/user-attachments/assets/b04ced73-3f63-4fde-8268-972027020c5b" />



**Output:**

<img width="1182" height="263" alt="image" src="https://github.com/user-attachments/assets/de595766-43c2-4f6b-b278-3c130ebcd3b9" />

**Question 2**
---
-- <img width="904" height="372" alt="image" src="https://github.com/user-attachments/assets/3cdfa8ba-4d6c-4669-be96-69fd3722e2c3" />


sql
-- <img width="698" height="141" alt="image" src="https://github.com/user-attachments/assets/65e8df45-8ee6-4979-bc0d-4d247cd602c2" />



**Output:**

<img width="1189" height="278" alt="image" src="https://github.com/user-attachments/assets/cad606db-e389-4582-8bbc-7adc0ef41317" />


**Question 3**
---
-- <img width="1396" height="515" alt="image" src="https://github.com/user-attachments/assets/8c16b9ba-6abc-4da4-9020-954b89398a7c" />


sql
-- <img width="433" height="175" alt="image" src="https://github.com/user-attachments/assets/e1356fa1-692b-4619-8f17-b8fa5d08c5f0" />



**Output:**

<img width="1188" height="381" alt="image" src="https://github.com/user-attachments/assets/a5d42875-17f2-4d17-b99c-fc63982a599a" />


**Question 4**
---
-- <img width="1369" height="350" alt="image" src="https://github.com/user-attachments/assets/bf3afc54-8290-4d3a-8273-39d59fe6b8ab" />


sql
-- <img width="461" height="218" alt="image" src="https://github.com/user-attachments/assets/a8858dac-0cda-4abf-9788-caf20c1ce6ac" />



**Output:**

<img width="1209" height="305" alt="image" src="https://github.com/user-attachments/assets/24dbd520-2574-4190-96eb-a82ef35a9466" />


**Question 5**
---
-- <img width="1393" height="359" alt="image" src="https://github.com/user-attachments/assets/d543d897-0ad1-4b31-8f6e-030d5c02d985" />


sql
-- <img width="624" height="171" alt="image" src="https://github.com/user-attachments/assets/78bd4e99-c063-46b5-80ec-7bb33dea5e3a" />



**Output:**

<img width="1207" height="283" alt="image" src="https://github.com/user-attachments/assets/e51dab42-f5ca-4d13-8b45-078dd70f3735" />


**Question 6**
---
-- <img width="1398" height="353" alt="image" src="https://github.com/user-attachments/assets/e6acd763-41d5-41ac-82c4-cba580cb2aed" />


sql
-- <img width="765" height="236" alt="image" src="https://github.com/user-attachments/assets/25e9fdb3-bc6b-4971-ad3a-1adc9ade299a" />
6


**Output:**

<img width="1223" height="293" alt="image" src="https://github.com/user-attachments/assets/ef13ef3e-961d-448f-9a22-029c4e8c164c" />

**Question 7**
---
-- <img width="1408" height="258" alt="image" src="https://github.com/user-attachments/assets/bf935321-3ee3-4845-a665-f3b28a472ce6" />


sql
-- <img width="565" height="103" alt="image" src="https://github.com/user-attachments/assets/9a604f32-37f7-4796-a512-02db3cd551b8" />



**Output:**
<img width="1219" height="263" alt="image" src="https://github.com/user-attachments/assets/c4e4b4b4-0052-454d-b6e7-6e29655afb43" />


**Question 8**
---
-- <img width="1208" height="457" alt="image" src="https://github.com/user-attachments/assets/5026632e-99ca-4f50-a8bb-b47eb57c2140" />


sql
-- <img width="440" height="230" alt="image" src="https://github.com/user-attachments/assets/1fef2933-3cd3-44cc-8f58-692a5fdf7514" />



**Output:**

<img width="1207" height="416" alt="image" src="https://github.com/user-attachments/assets/3073dc54-c775-4080-976a-b843ee9064b5" />

**Question 9**
---
-- <img width="1396" height="449" alt="image" src="https://github.com/user-attachments/assets/0beb88ce-0b5e-4776-a119-e3a78ac010cf" />


sql
-- <img width="619" height="251" alt="image" src="https://github.com/user-attachments/assets/c01dd7d2-5c20-447b-b58a-e786a3a456d8" />



**Output:**

<img width="1222" height="346" alt="image" src="https://github.com/user-attachments/assets/a3677259-94e4-42e6-8336-b27697f59349" />

**Question 10**
---
-- <img width="1387" height="506" alt="image" src="https://github.com/user-attachments/assets/ac385122-8bc8-40a6-925b-7495d91788f9" />


sql
-- <img width="784" height="338" alt="image" src="https://github.com/user-attachments/assets/c1b1878a-8465-4a9a-8731-fc47815be1aa" />



**Output:**

<img width="1246" height="334" alt="image" src="https://github.com/user-attachments/assets/c26caa9a-bb53-47e0-92fe-7909edb703e3" />


## RESULT
<img width="1421" height="192" alt="image" src="https://github.com/user-attachments/assets/2f78852e-d574-438a-b188-0188f8a38cfc" />

Thus, the SQL queries to implement different types of constraints and DDL commands have been executed successfully.
