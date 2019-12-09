# MentorBot
MentorBot: ChatBot for students

##### Technologies Used:
  * NodeJS
  * JAVA
  * MongoDB

##### Libraries used:
  * **Express** for *NodeJS*
  * **Socketio** for *NodeJS*
  * **Socketio** for *JAVA* in Android Studio
  
##### API used: DialogFlow



### How it works

The **Android app** will send data to a server and the server sends it in turn to the **DialogFlow API** which has already been trained extensively.

The API will **generate** a response and send it to the **server**, which parses the response from the API retrieves the required information from the **MongoDB Database**.

The information is then sent to the android app which is then put on the viewport for an aesthetic response.

**SocketIO** is used to establish the connection *between the Server and the Android App*
