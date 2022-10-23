# evive-menu-ordering

To run the project:

Importing the project
Open eclipse
Open up any workspace
Create a new java project, name it anything
Right click on the “src” of the new project, click import, and select “Archive File”, then next
Click on “browse” and select the evive-oa.jar file from wherever you downloaded it to
Hit finish

Adding JUnit for testing
Go to module-info.java, hover over the error, and select the first quick fix “Fix project setup…”
Alternatively, right click on the project, hover over “Build Path” and then select “Configure Build Path”
Go to the libraries page, and make sure that Modulepath is selected
Select “Add Library”, and then select “JUnit.” Click “Next” and then “Finish”
Click “Apply and close”

Running the program
Run “MenuOrdering.java” to give the program inputs from the console (also open the console for this)
Run “OrderTests.java” to run the tests
If a ClassNotFoundException occurs, restart the workspace (File -> Restart)
