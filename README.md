```sql
-- A bit about me 🧐

-- Creating a fictional table named 'rishabh' to store my bio information
CREATE TABLE rishabh (
    name VARCHAR(50),
    about TEXT,
    profession VARCHAR(100),
    learning VARCHAR(200),
    collaboration_interests VARCHAR(500),
    interests TEXT,
    email VARCHAR(100)
);

-- Inserting data into the table 'rishabh'
INSERT INTO rishabh (name, about, profession, learning, collaboration_interests, interests, email)
VALUES (
    'Nikhil',
    'Hi, this is Nikhil 👋',
    'Backend Developer',
    'Deep Learning and Neural Networks',
    'Collaborate on Open-Source projects',
    'Exploring different technologies',
    'nikhil25803@gmail.com'
);

-- Querying the 'rishabh' table to display my bio
SELECT * FROM rishabh;
