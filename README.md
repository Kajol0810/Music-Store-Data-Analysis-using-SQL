# Music-Store-Data-Analysis-using-SQL

Examinded the dataset with the help of SQL queries and help the store to under the business growth.



1.	Who is the senior most Employee based on Job title?
SELECT * FROM employee
	ORDER BY Levels DESC
	Limit 1;
![image](https://github.com/Kajol0810/Music-Store-Data-Analysis-using-SQL/assets/59485729/901ee824-53ca-45fc-9995-1ed977835e96)


 2.	Which countries have the most invoices?
SELECT COUNT(*) AS c, billing_country 
	FROM invoice
	GROUP BY billing_country
	Order by c ASC;

![image](https://github.com/Kajol0810/Music-Store-Data-Analysis-using-SQL/assets/59485729/2fcb4946-431c-463c-8db8-aa8335d748c9)

3.	What are top 3 values of total invoices?
SELECT total FROM invoice
	ORDER BY total DESC
	limit 3;


![image](https://github.com/Kajol0810/Music-Store-Data-Analysis-using-SQL/assets/59485729/260141b0-5801-4920-843b-5aa5fae3aeb7)




 
