cs241-Honor
===========
A social networking app that exchange data with the people you passed by, something like the Nintendo 3DS's StreetPass fucntionality. The app will get people's geo location, the longtitude and latitude. Based on the longtitude and latitude, we can calculate the distance between two people. If two people's distance is less than a certain threshold, say 10 meters, the app would exchange their status. Every 10 seconds the app would send request to the sever to see if there are any people nearby. If multiple response are returned, the app would use multithread to calculate all their distance at once. We also added a function that can post messagaes at certain location and when people come across that location, they will also receive that message.

[Project Video]( https://www.youtube.com/watch?v=0efyoXxzp2E&list=UUrLVgoBNuZN96Cryp7atRxg)
  
  
