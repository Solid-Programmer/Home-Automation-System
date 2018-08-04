# Home-Automation
Home Automation System using Raspberry Pi (Internet of Things)

This project contains a folder named "website", a SQL Database backup named "home automation system" and report named "Final Report.pdf".


Below are the steps to run "Home Automation System" application on your PC:

	Step 1: Configuring the XAMPP server:
		Install 'XAMPP' in windows or LAMP for linux. Remember to give port no as "8080" instead of 80, hostname as "root" and no password.
		Note: If you give some other values during installation then update that values in "connection.php" inside website folder.
		Copy and paste website folder in htdocs folder inside C:/xampp/htdocs/
		
	Step 2: Restoring the database:
		Install 'MySQL' and 'MySQL GUI Tools' in your PC.
		Open 'MySQLAdministrator' in MySQL GUI Tools folder.
		Click on Restore -> Open Backup File -> Choose Backup file -> Start Restore.
		
	Step 3: Run the website:
		Open any web browser (preffered Google Chrome).
		Put url as localhost:8080/website.
		Thats it! Home automation website is in front of you.
		Add device and control it by either click event or voice event by saying "Device name OFF" or "Device name ON". For eg. : Fan on, Bulb off etc.
		
		
		
Created by: 
Samar Khan     - 12BCE1006
Sachin Katiyar - 12BCE1021
