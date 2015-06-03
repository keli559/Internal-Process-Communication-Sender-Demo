# Internal Process Communication Sender Demo

This application is meant to send string "Hello World" to the Receiver
if successful, the Receiver would appear on screen:

               WM_CopyData from: 3819
               Received string "Hello World!" at 6/3/2015

Application:

1. Put "Hello World!" message into a data structure called "COPYDATASTUCT"
2. Find receiver by its app title "ReceiverMainForm" and its Class "TReceiverMainForm" (debug window: a pop-up window should show up with non-zero integers)
3. Send message in COPYDATASTRUCT through WM_COPYDATA code to receiver

This demo is written in C# Visual Studio 2015, Console application. It only constructs the sender part, the receiver part was previously constructed to receive messages from other apps. 
