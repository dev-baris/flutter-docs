Build & Run:
------------

### Run the Android Application:

1.  In the target selector, select an Android device for running the app. If none are listed as available, select Tools> Android > AVD Manager and create one there. For details, see [Managing AVDs.](https://developer.android.com/studio/run/managing-avds) Click the run icon in the toolbar, or invoke the menu item Run > Run. Locate the main Android Studio toolbar:
2.  If you don't use Android Studio or IntelliJ you can use the command line to run your application using the following command:

`flutter run`


[![build](images/build-1.png)](images/build-1.png)

### Run the iOS Application:

1.  The first thing that we require in hand is a test flutter app on our Mac
2.  Before we start testing our flutter app on the iPhone you need to make sure that our phone trusts us as a developer on that device. To do that follow this path go:

`Settings > General > Device Management or Profile > (Tap On) Trust “Your Developer Name”`


4.  To test or deploy our flutter app to a physical device we first need to enable physical device deployment in Xcode using Apple ID or an Apple Developer account. And we also need to set up a package manager to manage flutter plugins that are to be used in the project.
5.  First, we are going to install a third-party package manager called CocoaPods to manage flutter plugins that our project might depend on. To install and set up cocoapod the below command needs to be executed successfully in the terminal.

`$ sudo gem install cocoapods`

After we are done with the cocoapod installation we will proceed to locate the Runner.xcworkspace file inside the ios folder in our project directory. Then we need to open this file on the Xcode with a double click. OR write command

`$ open ios/Runner.xcworkspace`
