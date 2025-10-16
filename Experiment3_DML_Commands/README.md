# Experiment 3: DML Commands

## AIM
To study and implement DML (Data Manipulation Language) commands.

## THEORY

### 1. INSERT INTO
Used to add records into a relation.
These are three type of INSERT INTO queries which are as
A)Inserting a single record
**Syntax (Single Row):**
```sql
INSERT INTO table_name (field_1, field_2, ...) VALUES (value_1, value_2, ...);
```
**Syntax (Multiple Rows):**
```sql
INSERT INTO table_name (field_1, field_2, ...) VALUES
(value_1, value_2, ...),
(value_3, value_4, ...);
```
**Syntax (Insert from another table):**
```sql
INSERT INTO table_name SELECT * FROM other_table WHERE condition;
```
### 2. UPDATE
Used to modify records in a relation.
Syntax:
```sql
UPDATE table_name SET column1 = value1, column2 = value2 WHERE condition;
```
### 3. DELETE
Used to delete records from a relation.
**Syntax (All rows):**
```sql
DELETE FROM table_name;
```
**Syntax (Specific condition):**
```sql
DELETE FROM table_name WHERE condition;
```
### 4. SELECT
Used to retrieve records from a table.
**Syntax:**
```sql
SELECT column1, column2 FROM table_name WHERE condition;
```
**Question 1**
--<img width="1157" height="873" alt="image" src="https://github.com/user-attachments/assets/6a3287e6-2161-4f6b-99ff-3b88c6fbcad6" />


sql
-- <img width="447" height="253" alt="image" src="https://github.com/user-attachments/assets/7e058989-9a46-4d3a-96ba-a3873ffd12a0" />



**Output:**

<img width="1230" height="389" alt="image" src="https://github.com/user-attachments/assets/797b570c-fef6-4564-9da5-bd13e877accb" />


**Question 2**
---
-- <img width="1417" height="661" alt="image" src="https://github.com/user-attachments/assets/42af60c8-8c1c-4c45-802b-6c0adfc744fe" />


sql
-- <img width="458" height="172" alt="image" src="https://github.com/user-attachments/assets/052b1634-b80b-4027-bd7d-140d71736a6b" />



**Output:**

<img width="1206" height="509" alt="image" src="https://github.com/user-attachments/assets/23c5d6cc-bbfd-4824-a703-23c2c3036cf4" />


**Question 3**
---
-- <img width="1234" height="556" alt="image" src="https://github.com/user-attachments/assets/2dc74243-133d-40c0-b4c2-bb7f3e89d8ec" />


sql
-- <img width="414" height="151" alt="image" src="https://github.com/user-attachments/assets/133f9a45-2efb-4e86-9611-a04ecc466fb5" />



**Output:**

<img width="1222" height="391" alt="image" src="https://github.com/user-attachments/assets/a4ed1422-63d9-497c-9506-d27dbf081e5d" />

**Question 4**
---
-- <img width="1110" height="335" alt="image" src="https://github.com/user-attachments/assets/31bdaca0-e4b8-4dce-aeb9-1326e4c45f98" />


sql
-- <img width="418" height="131" alt="image" src="https://github.com/user-attachments/assets/d10c227a-d584-430e-836e-35672e1006ec" />



**Output:**

<img width="1220" height="631" alt="image" src="https://github.com/user-attachments/assets/e62ea690-1c70-4eba-84e6-c5aa73469232" />


**Question 5**
---
-- <img width="1390" height="639" alt="image" src="https://github.com/user-attachments/assets/d0a30fe2-0aed-4db9-bbe2-959fa7147ff2" />


sql
-- <img width="433" height="190" alt="image" src="https://github.com/user-attachments/assets/7910ec85-062b-4e63-8184-e513e9fb8b44" />



**Output:**

<img width="1232" height="357" alt="image" src="https://github.com/user-attachments/assets/a1194daa-c5c4-4773-8067-a71d0b55e4a3" />


**Question 6**
---
-- <img width="1384" height="514" alt="image" src="https://github.com/user-attachments/assets/4c6458b5-c05a-45b8-9e3d-0ec0c5d8efb7" />


sql
--<img width="388" height="183" alt="image" src="https://github.com/user-attachments/assets/571a9731-225f-4d0e-bdc7-d77e2ba774a7" />



**Output:**

<img width="1226" height="510" alt="image" src="https://github.com/user-attachments/assets/dbf4fcc7-0045-442a-ac10-2af68fe99cab" />


**Question 7**
---
-- <img width="1397" height="569" alt="image" src="https://github.com/user-attachments/assets/1eb5c2fa-d85f-437f-8974-9074add1c8e1" />


sql
--<img width="444" height="130" alt="image" src="https://github.com/user-attachments/assets/174eb061-5091-41db-9fa3-83ad4f024a01" />



**Output:**

<img width="1226" height="567" alt="image" src="https://github.com/user-attachments/assets/e153350f-3d05-4cfe-89b0-6fde7f32ae5d" />


**Question 8**
---
-- <img width="1407" height="482" alt="image" src="https://github.com/user-attachments/assets/9e8958df-bcda-404e-bd98-0e1b6e0198f9" />


sql
-- <img width="492" height="129" alt="image" src="https://github.com/user-attachments/assets/42ae1bd7-4d7c-4959-ac8e-25b909c1ef5b" />



**Output:**

<img width="1209" height="411" alt="image" src="https://github.com/user-attachments/assets/80d33c42-fbd1-486b-8383-e29a7c93aee7" />


**Question 9**
---
-- <img width="1396" height="565" alt="image" src="https://github.com/user-attachments/assets/806b9296-0bb2-4549-9aa4-75d968c46904" />


sql
-- <img width="563" height="154" alt="image" src="https://github.com/user-attachments/assets/6a5ff7fe-11a7-41da-9afb-4a5913a9dc3b" />



**Output:**

<img width="1197" height="441" alt="image" src="https://github.com/user-attachments/assets/3083d0ad-7e81-473b-8875-f682bd85e0f3" />

**Question 10**
---
-- <img width="1409" height="523" alt="image" src="https://github.com/user-attachments/assets/9c5bf156-9d31-4cce-9862-b41e6a163ba5" />


sql
-- <img width="787" height="140" alt="image" src="https://github.com/user-attachments/assets/25721932-44b4-4a89-8343-8a31dcaa18b6" />



**Output:**

<img width="1213" height="677" alt="image" src="https://github.com/user-attachments/assets/6d54063f-38f4-458e-b59b-2e7240936b9f" />


## RESULT
<img width="1416" height="168" alt="image" src="https://github.com/user-attachments/assets/73a93c0b-b23d-4be3-a6a9-b10d731d3888" />


Thus, the SQL queries to implement DML commands have been executed successfully.
