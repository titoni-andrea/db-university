QUERY
1) SELECT * FROM students WHERE date_of_birth >= '1990-01-01' AND date_of_birth <= '1990-12-31' 
2) SELECT * FROM courses WHERE cfu > 10;
3) SELECT * FROM students WHERE date_of_birth <= DATE_SUB(CURDATE(), INTERVAL 30 YEAR);
4) SELECT * FROM courses WHERE year = 1 AND period = 'I semestre';
5) SELECT * FROM exams WHERE date = '2020-06-20' AND hour > '14:00:00';
6) SELECT * FROM degrees WHERE level = 'magistrale';
7) SELECT MAX(department_id) FROM degrees;
8) SELECT * FROM teachers WHERE phone IS NULL;
9) INSERT INTO `students` (`id`, `degree_id`, `name`, `surname`, `date_of_birth`, `fiscal_code`, `enrolment_date`, `registration_number`, `email`) VALUES (NULL, '19', 'Andrea', 'Titoni', '2002-08-02', 'TTNNDR02M02E349W', '2024-06-04', '1244322', 'blablabla@gmail.com');
10) UPDATE teachers SET office_number = 126 WHERE name = 'Pietro' AND surname = 'Rizzo';
11) DELETE FROM students WHERE fiscal_code = 'ttnndr02m02e349w';