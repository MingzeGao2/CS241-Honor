Progress: Week Nov2 - Nov 8 The group meet together, decided to build an app to connect to nearby people. The app should get geometric infromation from user and upload it to our database. The app then search for devices within certain area.

Hackthon - Nov15 We seperated the team into two parts, one response for the android java part, other part reponse for the NDK jni part. The android java part made up the user interface for the app and used the Android api's to get the position information for the app. The java part also managed to connect to the database to upload the position information and the status of each user posted. Then the java part pass the position information to the jni part. The jni part received the information and use multithread to calcualte the distance between each users, if the distance is less than some certain threshold, eg. 10m, both user would receive the status message of each other and complete a "passby action". The app would send the request for update the positon information every 3 seconds. We finished the java part and jni part seperately during the hackthon.

Dec 6,7 Final debug to make our app run.

Difficulties: Since this is the first app I have ever built, even configuring the SDK and NDK things are not easy. Also, the part that transmitting data between JAVA code and C code are also somehow causing a lot of trouble.

Thought: Even though we finished all the functions we initially designed, the app still have alot of potential to improve. Eg. the formula to calculate the distance is no accurate enough. Also, constantly querying the database is costly for electricity.
