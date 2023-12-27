# Weather-Application
Mobile Automation Framework  For Weather Application

Environment Setup
 I have used different Technologies in building the Mobile framework and Isntall the following on my local machine
 1) JDK 11 
 2) Node Js v18.17.1 
 3) Android Studio IDE
 4) Build an Emulator 
 5) Appium Server
 6) Appim Inspector and I have used UiAutomatorViewr in inspecting the elements
 7) Eclipse IDE and install some plugins like (Cucumber, TestNG , BrowserStack) From it's Market Place
 8) Apache Maven 3.9.5

Define Some Envrioment Variables like
JAVA_HOME , ANDROID_HOME , NODE_HOME 
define paths for adb , android , emulator , apkanalyzer from the SDK folder 

check all the necessary dependencies for installation using appium-doctor command 

==========================================================================================================================================================================


Execution Tests
under the src/test/java I have a package called tests with 2 classes HomeTestScreen , ValidationIconsScreen

So you can Start Execute anyone of these classes 

I have Implemenet The Appium Server to run Programmatically by the help of AppiumDriverLocalService class So You can start , stop and configer the Appium Server without need to do it manually

