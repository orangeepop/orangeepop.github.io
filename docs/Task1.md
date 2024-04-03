# Creating a JavaFx Project

1. Open IntelliJ IDEA and click on "Create New Project" or go to "File" > "New" > "Project".

2. Select "Java" from the left sidebar and choose "JavaFX Application" from the list of project templates.

3. Enter a name for your project and choose a location to save it. Click "Next".

4. In the "Project SDK" dropdown, select the Java SDK you want to use for your project. If you don't have one installed, click on "New" and follow the prompts to install a Java SDK.

5. Click "Next" and review the project settings. Make sure the "Create module" checkbox is selected and the module name is set to the same name as your project. Click "Finish".

6. IntelliJ IDEA will create a new JavaFX project for you with a default package and a Main class.

7. In the Main class, you will see the following code:

```
public class Main extends Application {
    public static void main(String[] args) {
        launch(args);
    }
    
    @Override
    public void start(Stage primaryStage) {
        // Add your JavaFX code here
    }
}
```


