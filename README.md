


1) install apache tomcat
2)open tomcat directory and go to webapps folder
3)create a new folder within webapps with name "myapp"
4)create a new folder within myapp with mane "WEB-INF"
5)create a new folder inside  WEB-INF named classes craete java file (create the java servlet and other class files here)
6)go to web apps->ROOT->WEB-INF and copy the web.xml file
7)paste the copied xml file below the classes
8)create a servlet program "MyServlet.java" inside classes
9)after creating the servlet go to web xml file and map the servlet
10)crete a html page call the servlet say home page below WEB-INF
11)go to tomcat bin folder and run startup.bat
12)go to web browser and enter:
	"localhost:8080/myapp/home.html"
it will open the home page and show thw button on clicking the button it will go to next page and print "hello world"# servletexample
