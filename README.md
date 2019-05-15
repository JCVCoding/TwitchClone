To use this application you need to have Node/npm installed onto your computer as well as streaming / recording program. I recommend OBS and the instructions will assume you are using OBS and have a basic understanding of how to setup a stream.

In order to run this application you will need to run the following steps:
1) Open three terminal windows
2) In window one navigate into api folder, in window two navigate into client folder, and in window three navigate into rtmpserver folder.
3) In api folder run the following command: npm start. This will start a json-server on port 3001
4) In client folder run the following command: npm start. This will open the user interface on port 3000.
5) In rtmpserver folder run the following command: npm start. This will start the rtmp server on port 8000.
6) Use this url In your streaming software: rtmp://localhost/live
7) The stream key needs to match the id you see in the address bar on port 3000. This will be covered in the next few steps.

**AT THIS POINT YOU ARE READY TO CREATE A STREAM**
7) Sign in with Google and then click the create stream button.
8) Enter the title and description of your stream and then click submit. You have created your stream!
9) Now select your stream from the list and look at the url in the address bar. The number at the end is your ID and is also your stream key. Go back to OBS and input this number in the stream key section if you have not already.
10) Click Start Streaming in OBS. Thats it! You are now live :)

