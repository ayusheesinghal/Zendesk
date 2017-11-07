Zendesk Test Framework
The com.zendesk.testframework allows to 

 1. Verify that you are able to create a ticket
 2. Verify that you are able to add a comment to the ticket
 3. Verify that you are able to list all tickets for your Zendesk
 4. Verify that you are able to delete a ticket
 
Language used : Java
Test Framework: TestNG
Validations using: Rest Assured
Build and Run Instructions
Command Line
Install java
Update Java_Home
Check Maven is installed using this command. mvn -version
If Maven is not installed, install Maven
Download and unzip com.zendesk.testframework
Open Terminal/cmd and navigate to project location
Run mvn clean install

IDE
Install m2eclipse plugin in Eclipse
Unzip and import com.zendesk.testframework
Right click project explorer > Import... > Maven projects
Select project > Run as > Mvn Test or Run testng.xml as TestNG

Design Considerations
ZendeskProperties.java can be modified easily to update config related information( userid and token)
TestCase data can be modified easily and is laid separately from test cases
Additional input parameters can be added to NewTicket and Comment class to allow more input parameters in request
TestNG framework allows to prioritize test cases to ensure asynchronous results
		
