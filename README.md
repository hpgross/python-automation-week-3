# python-automation-week-3
Project for Week 3 of the Automating Real-World Tasks with Python course

This project contains modified python scripts and data from the course materials. The theme of this week is working with data at a car dealership.

reports.py is a script that generates a simple PDF of the data generated by other scripts using the ReportLab module.

emails.py uses the email and smtplib modules to generate an email message with a PDF generated by reports.py attached.

example.py is a simpler example of how the report and email modules are used for a very simple table of fruit.

car_sales.json contains simple sale records with id, car (car_make, car_model, car_year), price, total_sales as fields for data.

cars.py is the script that is modified the most from the origin.
It contains functions to calculate the model with the most revenue, the most sales, and the most popular year of car makes, and adds them to a summary
It then generates a file called cars.pdf inside /tmp/.
This files is then emailed to the user on the localhost.