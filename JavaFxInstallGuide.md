How to install JavaFx on Eclipse

1)Download the JavaFx Library:  https://gluonhq.com/products/javafx/
    Select by your distro and pick the version that you prefer
    
2)Extract this file wherever you want (the folder must not be deleted)

3)Open Eclipse and go to Help -> Eclipse Marketplace -> search on bar "fx" and install e(fx)clipse 3.*.*

4)Now create a new JavaFx project (go on File -> New -> Other -> JavaFx -> JavaFx Project)

5)Then click on Next -> Select the properties of your project (name, version jre ...) and once you're done click on Finish

6)Now go on Window -> Preferencies, search for User Libreries, click on New -> write a name you prefer -> Ok

7)Click on your new Library,then Add External JARs -> go on the folder that you have previously extract -> lib -> then select all the .jar file and click open, then Apply and Close

8)In your project now go on BuildPath -> Configure BuildPath -> Library -> click on Classpath -> Add Library -> User Library -> Next, then select your library and click Finish, after that click on Apply -> Apply and close

9)Right click on project -> Run as -> Run Configuration -> Arguments, in VM arguments copy and paste this --module-path "YOURJAVAFXPATH/lib" --add-modules javafx.controls,javafx.fxml  ,change path then Apply, and Run

10)Now JavaFx is installed, and this is your first project. Have fun!


