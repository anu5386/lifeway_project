Project tools:
IntelliJ
Downloaded project from spring.io 
Maven
JDK11
Java
Springboot
.Jar file for Web Service to initiate 

Please find the steps that I used to implement the project:

1. Extract Lifeway_Project_Anu.zip
2. There will be a folder named "demo 2" and a json file named "db.json"
3. Execute below command in terminal to create an endpoint that generates JSON request that will be used in Spring boot project.
	$ json-server --watch db.json
4. You should be able to now open this endpoint "http://localhost:3000/db"
	
	The message should look like below:
	
	{
  "": [
    {
      "id": "1",
      "message": "This is a test"
    },
    {
      "id": "2",
      "message": "to count number of characters"
    },
    {
      "id": "3",
      "message": "from a url"
    },
    {
      "id": "2",
      "message": "to count number of characters"
    }
  ]
}

5. Import the project using IntelliJ
6. Once imported, you can run the "CountcharactersController" to view the result on the console.
7. Run the services "RestServiceApplicationTests" to view the endpoint "http://localhost:8080/countcharacters"