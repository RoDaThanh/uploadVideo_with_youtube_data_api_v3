# uploadVideo_with_youtube_data_api_v3
Try to integrate with youtube data api v3 to upload a video to youtube channel

This was made for upload video youtube automatically, but it needs to be sig in. Therefore I stop here.

Before running the sample, client_secrets.json must be populated with a client ID and client secret. You can create an ID/secret pair at:

https://code.google.com/apis/console

To build this code sample from the command line, type:

mvn compile

To run a code sample from the command line, enter the following:

mvn exec:java -Dexec.mainClass="FULL_CLASS_NAME"

ex: mvn exec:java -Dexec.mainClass="com.youtube.ApiExample"

remember to replace your video to upload to your channel.

Pro and cons:
 
- Able to upload video with one command
- Save time

Cons:

- youtube only alow 10.000 units means ~ you can only post 6 videos 
- Have to verify account, (oauth2)


### Bottom line is: 
This was made for upload video youtube automatically, but it needs to be sig in. Therefore I stop here.