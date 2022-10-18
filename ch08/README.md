# Download JavaFX
https://gluonhq.com/products/javafx/



To run the application from the command line, use the following:
```shell
mvn javafx:run
```
## IMPORTANT NOTE

If you are using a JDK greater than version 1.8, the JavaFX libraries may not be bundled with the JDK itself. When running the application from your IDE, you will likely need to add the following:
```shell
--module-path=<path-to-javafx-sdk>/lib/ \
--add-modules=javafx.controls,javafx.graphics,javafx.fxml,javafx.media
``` 
* Paste the following in VM options:
```
--module-path "D:\DATA\JAVA\old_jdks\javafx-sdk-19\lib"  --add-modules=javafx.controls,javafx.fxml
```


We are making use of the mvvmFX framework to assemble the UI. To make this work with Spring Boot, the application launcher looks as depicted here: