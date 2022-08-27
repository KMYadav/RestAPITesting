# Rest API Testing - Rest Assured (JAVA)

End point/Base URL: Address where API is hosted on the server.

HTTP methods which are commonly used to communicate with Rest API's are - GET, POST, PUT and DELETE -CRUD - operations.

GET - The GET method is used to extract information from the given server using a given URL.
While using GET request, it should only extract data and should have no other effect on the data. No Payload/Body required.
How to send input data in GET?
Ans. Using Query Parameters

POST -  A POST required is used to send data to the server, for example, customer information, file upload, etc using HTML forms.
How to send input data in POST?
Ans. Using Form Parameters Body/Payload

PUT - Replace all current representations of the target resource with the uploaded content.

DELETE - Removes all current representations of the target resource given by a URL.

Resources: Resources represent API/Collection which cxan be accessed from the server
           Google.com/maps
           Google.com/search
           
Path Parameters:
Path parameters are variable parts of URL path. They are typically used to point a specific resource within a collection, such as auser identified by ID
                https://www.google.com/Images/112345
                https://www.google.com/docs/52624636
                
Query Parameters:
QUery Parameter is used to sort/filter the resources.
QUery parameters are identified with ?""
https://wwww.amazon.com/orders?sort_by=2/20/2022

