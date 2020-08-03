# drupal-8.6.4
voxteneo-drupal_8.6.4-Test

MySql:
	file: Database-Mysql/tester8.sql
	database: tester8
	user: root
	pass:
	
Drupal: (8.6.4)
	user: admin
	pass: 123

Step Install Drupal on Localhost:
1. Drupal version 8.6.4
2. using composer for install Drupal (run from command line)
	composer create-project drupal/recommended-project my_site_name_dir
3. create Mysql database (sample: tester8)
4. run install Drupal, from localhost and set for database name (tester8)
5. wait and see

Step copy file to Localhost:
1. Drupal version 8.6.4
2. clone "https://github.com/rsidiq2020/drupal-8.6.4.git" to your localhost folder
3. create Mysql database (name: tester8)
4. and run