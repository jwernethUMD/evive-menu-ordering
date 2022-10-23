# evive-menu-ordering

## Importing the project
1. Open Eclipse
2. Open up any workspace
3. Create a new java project, name it anything
4. Right click on the “src” of the new project, click import, and select “Archive File”, then next Click on “browse” and select the evive-oa.jar file from wherever you downloaded it to
5. Hit finish

## Adding JUnit for testing
* Go to module-info.java, hover over the error, and select the first quick fix “Fix project setup…”
* Alternatively, right click on the project, hover over “Build Path” and then select “Configure Build Path”
  - Go to the libraries page, and make sure that Modulepath is selected
  - Select “Add Library”, and then select “JUnit.” Click “Next” and then “Finish”
  - Click “Apply and close”

## Running the program
* Run “MenuOrdering.java” to give the program inputs from the console (also open the console for this)
* Run “OrderTests.java” to run the tests
  - If a ClassNotFoundException occurs, restart the workspace (File -> Restart)

## Alternatives
The program can run in other spaces besides Eclipse as long as the .jar file can be imported, the .java files can be run, and the **JUnit library** is made available to the program.
