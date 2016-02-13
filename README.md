# Ionic-APP
My 1rst IONIC + CORDOVA app. 


1- Start the Json-server:
      
      cd json-server
      
      json-server --watch db.json
      
      
2- To run the app from the mobile  you need to update the  localhost to the IP address of your computer:

     
For example, if your IP address is 192.168.1.121, then the above line should be as follows:


      .constant("baseURL", "http://192.168.1.121:3000/")


Save the changes.


Make sure that your json-server is up and running


#Configure, build and Deploy to an Android Emulator

Open a terminal window and go to the conFusion folder where you have your Ionic application.
Next, add the Android platform to your app by typing the following at the prompt:

     ionic platform add android
Then, build the app for the Android platform as follows:


     ionic build android
     
Finally, you can deploy the app to the Android emulator by typing the following at the prompt:

     ionic emulate android
     

If you happen to have an Android device and are willing to use it for development, then configure the device to allow development on the device. The exact procedure depends on the manufacturer and model of the device. Check for these instructions either within your device manual, or online.
Connect your Android device to the computer. Then, at the command prompt, type the following:

     ionic run android
     
This should deploy the app to the device and open the app on the device.

