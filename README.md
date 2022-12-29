# Mobile Testing Q&A

## Most used ADB commands

![image](https://user-images.githubusercontent.com/70295997/209899708-28be996f-94aa-4cbb-be22-6173b2015b45.png)

## Tools used to record crash logs for iOS

![image](https://user-images.githubusercontent.com/70295997/209899629-eadd2d56-35b6-4bd0-b276-5c601413f972.png)

## Important things to remember while testing mobile apps

![image](https://user-images.githubusercontent.com/70295997/209899814-be8745b2-b35d-4565-8c60-af68c74cae20.png)
![image](https://user-images.githubusercontent.com/70295997/209899887-c6d1f54b-e921-4461-9632-e1811399d14a.png)
![image](https://user-images.githubusercontent.com/70295997/209900037-ab2e8de4-dfb9-4a65-8a47-698d002ff5f7.png)

## Kinds of interruption testing on mobile apps

![image](https://user-images.githubusercontent.com/70295997/209900182-3b840014-b118-444c-9a66-bfcca7e783aa.png)
![image](https://user-images.githubusercontent.com/70295997/209900307-7b9547fc-cf4b-465e-b00f-d5fea5b07a36.png)
![image](https://user-images.githubusercontent.com/70295997/209900368-999155dc-d4e7-4f7a-a892-16b22be6ad61.png)

## Difference between mobile and web application testing

![image](https://user-images.githubusercontent.com/70295997/209900435-f527c334-70cc-4cbc-947a-71234de13f5d.png)
![image](https://user-images.githubusercontent.com/70295997/209900511-55e92402-7855-4363-acd8-f4dac3237b89.png)

## What is mobile fragmentation?

![image](https://user-images.githubusercontent.com/70295997/209900576-d766aeb5-17fc-4b13-ae0d-49c692b6843e.png)
![image](https://user-images.githubusercontent.com/70295997/209900598-c711ee31-f0cf-4980-93c5-ea8ae3d06a9f.png)
![image](https://user-images.githubusercontent.com/70295997/209900627-f30ae56e-30a6-43b0-8b65-80871471ae8c.png)

## How to test a home screen of an app?

![image](https://user-images.githubusercontent.com/70295997/209900744-d06d2390-a5be-4310-971c-97c28e822296.png)
![image](https://user-images.githubusercontent.com/70295997/209900786-fce3924f-f612-42db-9a01-fb3994c1551d.png)
![image](https://user-images.githubusercontent.com/70295997/209900821-c7c6386a-d905-4e0b-94b2-5935a53b4d88.png)
![image](https://user-images.githubusercontent.com/70295997/209900905-8c614798-a702-4805-a8bd-7992dc241141.png)

## What devices to use for mobile testing and how to them set up?

![image](https://user-images.githubusercontent.com/70295997/209901049-b3eedb2f-804e-42a5-9139-5ca3728cb9b9.png)
![image](https://user-images.githubusercontent.com/70295997/209901211-84dc2943-27fa-49c3-a6c5-487e28a20ff9.png)
![image](https://user-images.githubusercontent.com/70295997/209901316-d1a194f4-ce69-4150-a7e9-b35097f6856b.png)

## List top favorite mobile testing tools and why. Give examples.

![image](https://user-images.githubusercontent.com/70295997/209901478-9a9b38c9-8cf6-42d3-b2f6-721573be8811.png)
![image](https://user-images.githubusercontent.com/70295997/209902220-895c426f-e1d3-4771-8b23-39fa8338cc95.png)

## List top favorite mobile debugging tools and why. Give examples.

![image](https://user-images.githubusercontent.com/70295997/209902340-6e537bbc-2108-44e1-b155-9c2a6787244b.png)
![image](https://user-images.githubusercontent.com/70295997/209902424-1677a2f0-e00f-43d9-bd50-7341a9f3d4b0.png)
![image](https://user-images.githubusercontent.com/70295997/209902492-6eb28150-d218-434a-bd1f-763ac032eb03.png)

## What is ANR and how does it differ from crashes?
![image](https://user-images.githubusercontent.com/70295997/209902597-9885a188-2924-4e1c-89e2-1c9c93605465.png)
![image](https://user-images.githubusercontent.com/70295997/209902645-336df4ff-ac3c-4f7e-8903-956a46874ade.png)
![image](https://user-images.githubusercontent.com/70295997/209902728-9781d0cf-7d52-4e97-8699-a7520ad7d229.png)

## If you have several Android devices (virtual emulators and/or physical phones) connected to your machine, how do you install an application?

If you have multiple devices available but only one is an emulator, use the -e option to send commands to the emulator. If there are multiple devices but only one hardware device attached, use the -d option to send commands to the hardware device.

There is a difference in ADB commands used for installing mobile apps on Android devices vs emulators. In command 'adb [-d |-e | -s serial_number] install path_to_apk', the options in [] are the differentiators. -d is for device, -e is for emulator, -s is for serial number for either physical or virtual device.

      adb -s emulator-5555 install helloWorld.apk

![image](https://user-images.githubusercontent.com/70295997/209904192-26749182-7f27-4ccd-86d4-aae94c07fbdf.png)

## If you have an old version installed, and you don’t want to lose your data, how you install a new .apk file?

![image](https://user-images.githubusercontent.com/70295997/209905105-4311da1b-5d83-4af4-a8b4-e7303e5e4e63.png)

## I want to capture a video, How can I do it with an adb command?

![image](https://user-images.githubusercontent.com/70295997/209906473-321b125a-969a-4be6-b27e-d8347781b8a9.png)
![image](https://user-images.githubusercontent.com/70295997/209906532-e8c5aa0a-f428-4202-95fc-7cf8cb6db0b8.png)

## You started working on your device and you observe a crash. How do you collect logs?

![image](https://user-images.githubusercontent.com/70295997/209906650-c6030e5f-36c9-4d1e-896d-7d4caf7d9a98.png)
![image](https://user-images.githubusercontent.com/70295997/209906715-be1f2aef-3809-4b4d-870f-848da18058ee.png)

№№ How do you use adb bugreport command to collect the logs?

![image](https://user-images.githubusercontent.com/70295997/209906780-6648a836-978f-41b9-91fc-9bc7683110ec.png)
![image](https://user-images.githubusercontent.com/70295997/209906902-f5564be5-c84c-43f3-aeba-4ecaab7d34bd.png)

№№ What is the main difference between ‘adb logcat’ and ‘adb bugreport’?

![image](https://user-images.githubusercontent.com/70295997/209907030-ee4ecbba-e711-43cb-a90a-b52ee873ff04.png)
![image](https://user-images.githubusercontent.com/70295997/209907074-4fe7ed7e-91ec-4498-9e7d-49491a23fe32.png)

## You use the YouTube application, how you can get log file for YouTube?

![image](https://user-images.githubusercontent.com/70295997/209907246-680f03fc-249d-420c-84cd-510fde935b27.png)
![image](https://user-images.githubusercontent.com/70295997/209907319-64e72fec-8e67-4fa2-84d5-4a85c575a154.png)

## You use the Gmail app and you type and a crash happens. How do you justify that crash for this particular app?

![image](https://user-images.githubusercontent.com/70295997/209907467-9cbbc155-3953-46fb-a510-8bef09a7639d.png)
![image](https://user-images.githubusercontent.com/70295997/209907558-372c4b29-9387-4f57-92c3-5988be06fa38.png)
![image](https://user-images.githubusercontent.com/70295997/209907614-5e5ac435-291c-471a-ba71-805d2c7f08ef.png)

## If you open your log, what is the information you check for?

![image](https://user-images.githubusercontent.com/70295997/209907664-e7ad528b-2daa-496f-8234-36a4aeb9f8be.png)
![image](https://user-images.githubusercontent.com/70295997/209907714-6be2cb63-6d35-49b2-833b-d8f2036c862f.png)

## How to install an app on iOS devices?

![image](https://user-images.githubusercontent.com/70295997/209907860-5c6b04a6-c83e-4be1-b187-db3e73e7a304.png)

## How to install an app on iOS devices?

![image](https://user-images.githubusercontent.com/70295997/209908238-d63fe0a6-7a83-4c04-9904-9b4617a6e36d.png)
![image](https://user-images.githubusercontent.com/70295997/209908303-cba56c54-4b52-4098-ba40-5556ac08f324.png)
![image](https://user-images.githubusercontent.com/70295997/209908370-546d572e-4526-480f-a7c5-b3da6ac4a568.png)


To install a test app on an iOS device from your local machine using drag-and-drop, you can use the Xcode integrated development environment (IDE). Here is the general process for installing a test app on an iOS device using Xcode:

Connect the device to your machine: Use a USB cable to connect the device to your machine. Make sure that the device is recognized by Xcode and appears in the Devices window.

Drag and drop the app onto the device: In Finder (on macOS), navigate to the location where the test app is stored. Drag and drop the app onto the device in the Devices window in Xcode.

Wait for the app to install: The app will be installed on the device automatically. You can monitor the progress in the Xcode console.

Test the app: Use the app on the device to test its functionality and behavior. You can use the Xcode debugger to set breakpoints and step through the code, or use other tools and techniques to test the app.

Overall, using Xcode is a simple and straightforward way to install a test app on an iOS device from your local machine using drag-and-drop. This process does not require the use of any command-line tools or commands.

## How to enable Developer options on Android devices?

To enable Developer options on an Android device, you can follow these steps:

1. Open the Settings app: From the home screen or app drawer, tap the Settings icon to open the Settings app.
2. Scroll down and tap "About phone": Scroll down to the bottom of the Settings menu and tap the "About phone" option.
3. Tap "Software information": Scroll down to the bottom of the About phone menu and tap the "Software information" option.
4. Tap "Build number" seven times: Tap the "Build number" option seven times. You should see a message that says "You are now a developer!"
5. Go back to the main Settings menu: Tap the back arrow or button to return to the main Settings menu.
6. Enable Developer options: Scroll down to the bottom of the Settings menu and tap the "Developer options" option. Toggle the switch next to "Developer options" to the "On" position.
7. (Optional) Set up USB debugging: In the Developer options menu, toggle the switch next to "USB debugging" to the "On" position. This will allow you to debug your device using a computer and the Android Debug Bridge (ADB) tool.

Overall, enabling Developer options on an Android device is a simple process that allows you to access advanced developer features and settings. Once you have enabled Developer options, you can use them to test and debug your app, as well as customize your device's behavior and appearance.

## How to enable Developer on iOS devices?

To enable Developer options on an iOS device, you can follow these steps:

1. Open the Settings app: From the home screen or app drawer, tap the Settings icon to open the Settings app.
2. Tap "General": Scroll down to the bottom of the Settings menu and tap the "General" option.
3. Tap "Profiles & Device Management": Scroll down to the bottom of the General menu and tap the "Profiles & Device Management" option.
4. Tap your developer account: If you are a registered developer with Apple, you should see your developer account listed under the "Developer App" section. Tap your developer account to open the developer options.
5. Tap "Trust": Tap the "Trust" button to trust your developer account and enable Developer options on your device.
6. Enter your device passcode: Enter your device passcode to confirm the trust operation.
7. (Optional) Set up USB debugging: In the Developer options menu, toggle the switch next to "USB debugging" to the "On" position. This will allow you to debug your device using a computer and the Xcode integrated development environment (IDE).

Overall, enabling Developer options on an iOS device is a simple process that allows you to access advanced developer features and settings. Once you have enabled Developer options, you can use them to test and debug your app, as well as customize your device's behavior and appearance.

## What is Charles Proxy?

Charles Proxy is a popular tool for debugging, testing, and optimizing web and mobile applications. It is particularly useful for mobile testing because it allows you to intercept and inspect HTTP and HTTPS traffic from mobile devices. This can be useful for a wide range of testing and debugging scenarios, such as:

- Verifying that your app is sending and receiving data correctly
- Debugging issues with network requests or responses
- Analyzing the performance of your app's network communication
- Inspecting the data being sent and received by your app
- To use Charles Proxy for mobile testing, you will need to install the Charles Proxy software on your computer and configure your mobile device to use it as a proxy. 

Here is a general outline of the process:

1. Download and install Charles Proxy: Go to the Charles Proxy website and download the latest version of the software. Follow the instructions to install it on your computer.
2. Configure your mobile device: On your mobile device, go to the Wi-Fi settings and tap the name of the Wi-Fi network you are connected to. Scroll down to the "HTTP PROXY" section and tap "Manual". Enter the IP address of your computer and the port number used by Charles Proxy (usually 8888).
3. Start Charles Proxy: On your computer, open Charles Proxy and click the "Start" button to start capturing network traffic.
4. Use your app: On your mobile device, use your app as you normally would. Charles Proxy will capture and display the network traffic generated by your app.
5. Inspect the traffic: In Charles Proxy, you can inspect the traffic captured from your mobile device. You can view the request and response headers, payloads, and other details. You can also use the Charles Proxy tools to analyze and debug the traffic.

Overall, Charles Proxy is a powerful and useful tool for mobile testing that allows you to inspect and debug the network communication of your app. It can be particularly useful for identifying and troubleshooting issues with network requests and responses, and for optimizing the performance of your app.

![image](https://user-images.githubusercontent.com/70295997/209909995-ddd61c6c-f20f-4962-9a5d-60a04f1394c5.png)

## What is Fiddler?

Fiddler is a web debugging tool that allows you to intercept and analyze HTTP traffic between a client (such as a mobile device) and a server. It can be useful for mobile testing in a number of ways:

1. Debugging network requests: Fiddler allows you to view and analyze the network requests made by your mobile app, including the request and response headers, the body of the request and response, and any cookies or other metadata. This can be helpful for debugging issues with network requests, such as errors or timeouts.
2. Modifying network requests: Fiddler allows you to modify the network requests made by your mobile app in real-time. This can be helpful for testing different scenarios, such as different responses from the server or different network conditions.
3. Analyzing performance: Fiddler provides a range of performance metrics, such as the time taken to complete a request and the size of the request and response. This can be helpful for identifying and optimizing the performance of your mobile app.
4. Testing security: Fiddler allows you to intercept and modify SSL/TLS traffic, which can be useful for testing the security of your mobile app.

Overall, Fiddler is a powerful tool for mobile testing that can be used to debug, test, and optimize the network performance of your app. To use Fiddler for mobile testing, you will need to install the Fiddler app on your mobile device and configure your device to use Fiddler as a proxy server. You will also need to install the Fiddler desktop application on your computer and configure it to capture and analyze traffic.

![image](https://user-images.githubusercontent.com/70295997/209910320-4f86c112-268e-4875-bf7e-16b520aa2cca.png)














