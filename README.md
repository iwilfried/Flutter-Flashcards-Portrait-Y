Explanation of code:  
import statement:  
The import statement is used to import the libraries provided by the flutter SDK. So, here we have imported the ‘material.dart’ file.  
main() function: We also have a main function in which we have to write the statements that are to be executed. The return type of the main function is ‘void’.  
runApp (Widget widget) function: The void runApp takes a widget as an argument and sets it on a screen. It also gives the constraints to the widget to fit into the screen. It makes the given widget the root widget of the app and other widgets as the child of it.  
title: This property is used to provide a short description of the application. So, when the user presses the recent apps button on mobile the text in the title is displayed.  
theme: This property is used to provide the default theme to the application. So, we use the inbuilt class/widget named ThemeData(). Also in Themedata() widget, we have to write the different properties related to the theme. Here we have used the primarySwatch. It is used to define the default themecolor of the application. So to choose the color we have used the Colors class from the material library.  
home: It is used for the default route of the app. It means the widget defined in it is displayed when the application starts normally. So, here we have defined the Scaffold widget inside the home property.  

A new Flutter project.

## Getting Started

This project is a starting point for a Flutter application.

A few resources to get you started if this is your first Flutter project:

- [Lab: Write your first Flutter app](https://docs.flutter.dev/get-started/codelab)
- [Cookbook: Useful Flutter samples](https://docs.flutter.dev/cookbook)

For help getting started with Flutter development, view the
[online documentation](https://docs.flutter.dev/), which offers tutorials,
samples, guidance on mobile development, and a full API reference.
