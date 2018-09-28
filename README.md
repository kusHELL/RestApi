# RestApi
Using Rest Api via Python 

REST API
REST (REpresentational State Transfer) is an architectural style, and an approach to communications that is often used in the development of Web services. The use of REST is often preferred over the more heavyweight SOAP (Simple Object Access Protocol) style because REST does not leverage as much bandwidth, which makes it a better fit for use over the Internet. The SOAP approach requires writing or using a provided server program (to serve data) and a client program (to request data)

I have used GET option of RestApi for fetching data from database file(chinook.db),You can explore restapi by using PUT,POST,DELETE options of RestApi. 

PACKAGES INSTALLED IN PYTHON  
1. Flask
2. Flask-SQLAlchemy
3. Flask-Restful
4. SQlite3
5. Jsonify

INSTALLATION
Considering Python is installed and configured, type-
pip install flask flask-jsonpify flask-sqlalchemy flask-restful jsonify SQlite3

DATABASE
Chinook.db file is provided.You can check file using command "sqlite3 chinook.db". This command will connect you to the database for usage of it in program.
I have taken this database file from http://www.sqlitetutorial.net/sqlite-sample-database website.

PYTHON CODE
server.py file is provided. Just Execute it using command "python server.py".This will create 3 routes in your browser-

Route 1 -->http://127.0.0.1:5002/employees 
This will show the employees ID of employees.

Route 2 -->http://127.0.0.1:5002/tracks
This will show tracking details.

Route 3 -->http://127.0.0.1:5002/employees/8
This will show details of employee whose employee Id is = 8.

The format of data you will be getting in browser will json.

ABOUT
This is my First Github commit so please just let me know if there is any flaw, feel free to question and ask anything regarding this project.
I have refered to https://impythonist.wordpress.com/2015/07/12/build-an-api-under-30-lines-of-code-with-python-and-flask blog for this,special thanks to it.
