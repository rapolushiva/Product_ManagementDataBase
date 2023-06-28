# Product_ManagementDataBase
Product Management is used  to buy  or sell products in online. Insert the product data into database like mysql.  It will appear based on  particular product url as well as category of products in the bottom


Main changes in the above Product_Management_DB.zip file are:
  1)Mysql Port number 3307 to 3306
  2)In your local host create Database name as Product_Management_db
  3)The below commands are run in your terminal or commandprompt after download this zip
   -->cd Product_Management_DB (change the directory main project and makemigration command as follows) 
   -->python manage.py makemigrations(Afther the makemigrations migrate using next command)
   -->python manage.py migrate (After migrate different tables are created in the Database)
   -->python manage.py createsuperuser (it is used log into admin )
   -->Python manage.py runserver  (after login data enter into two diffeterent tables are one is category table  and another one                               is Products table)
   4)Enter the required urls show the web pages based on entered urls 
      
