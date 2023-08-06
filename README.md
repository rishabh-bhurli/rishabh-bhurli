```sql
-- A bit about me 

CREATE TABLE rishabh (
    name VARCHAR(7),
    about TEXT,
    working_on VARCHAR(100),
    learning VARCHAR(200),
    collaboration_interests VARCHAR(500),
    interests TEXT,
    email VARCHAR(100)
);

INSERT INTO rishabh (name, about, working_on, learning, collaboration_interests, interests, email)
VALUES (
    'Rishabh Bhurli',
    'Hi, this is Rishabh',
    'HTML CSS and JS',
    'JavaScript and React',
    'Collaborate on Open-Source projects',
    'Exploring different technologies',
    'iamrishabh9@gmail.com'
);

SELECT * FROM rishabh;
