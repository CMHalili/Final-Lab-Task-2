# Final-Lab-Task-2: Transforming ER into Relational tables

# Step by Step Process

## Step 1. Create the student table:
* Define username as a VARCHAR (50)
* Set username as the Primary Key

## Step 2. Create the assignment table:
* Define shortname as a VARCHAR (50) and set it as the Primary Key
* Define due date as a DATE and make it NOT NULL
*Define url as VARCHAR (255), which can be null

## Step 3. Create the submission table:
* Define username and shortname as VARCHAR (50)
* Define version as an INT
* Define submit date as a DATE and make it NOT NULL
* Set a composite primary key using (username, shortname, version)
* Add foreign key constraints referencing the student and assignment tables


