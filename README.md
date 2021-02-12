# Case

A) Used tech-stack
I have already explained code uploaded with the command line. Now for this part, I would like to explain the libraries I added to the project. 
In order to use data from an MS Excel file, I used openpyxl library. load_workbook( ) function is used when I had to access an MS Excel file in openpyxl module. The properties of Worksheet also helped with the data transportation between two files. 
The second technology I used is the Requests Module, which allows sending HTTP requests using Python. requests.get() method was used for making a request to a web page, and returning of the status code. The other Module that has been used is BeautifulSoup Module which is a powerful and fast library built for processing HTML or XML files that gets its name from the story told by a turtle in Alice in Wonderland. I used bs4 library for the Python BeautifulSoup Module for programs that parse HTML codes in a resource and for cutting only the areas I want.

B) A brief description of the challenges you face
I have faced with the timing issue. For scraping necessary metrics, I had to wait around 5 min for each result of problems. I figured it out by adding some static dummy data to my project. It worked for me because this part and the part I was testing doesn't affect each other, I always pay attention to modularity, because I believe it is the most significant part for being able to solve bugs.

C) What did you learn from this project?
I learned taking data from an MS Excel file and rearrange the file while coding. And also I haven't worked on web scraping before this Case. In short, I have learned how to take data from a website using python and using MS Excel as a database.

D) Answers of the additional questions
1) In this project, I used beautifulSoup library which led me to work with xml files. If I could use json format, this project would be significantly faster. Json is a language that is easy to read and use.  In fact, it has been developed on the basis that the XML language remains large and slow during data exchange. It takes less space than XML files. In a major project that does not require a strict security, using RESTful services is considerably more efficient than using Soap services because of this difference.
2) Application Programming Interface(API) is a software tool that allows two applications to communicate with each other. Data is stored in a database on a physical server. To get that data, talking to that database is necessary. That’s what an API does, it increases functionality. 

