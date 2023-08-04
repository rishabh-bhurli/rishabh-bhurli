```sql
-- A bit about me 

-- Creating a fictional table named 'rishabh' to store my bio information
CREATE TABLE rishabh (
    name VARCHAR(7),
    about TEXT,
    working on VARCHAR(100),
    learning VARCHAR(200),
    collaboration_interests VARCHAR(500),
    interests TEXT,
    email VARCHAR(100)
);

-- Inserting data into the table 'rishabh'
INSERT INTO rishabh (name, about, profession, learning, collaboration_interests, interests, email)
VALUES (
    'Rishabh Bhurli',
    'Hi, this is Rishabh',
    'HTML CSS and JS',
    'JavaScript',
    'Collaborate on Open-Source projects',
    'Exploring different technologies',
    'iamrishabh9@gmail.com'
);

-- Querying the 'rishabh' table to display my bio
SELECT * FROM rishabh;
