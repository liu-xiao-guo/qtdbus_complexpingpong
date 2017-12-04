This is a simeple Qt Dbus example. It is based on the complexingpong example from the Qt SDK. However, I added a simple property to it to get a QRect type, which is talked too much in the article at:

https://techbase.kde.org/Development/Tutorials/D-Bus/CustomTypes

The way of doing it is too much complicated in my sense. Comparatively, the method in this example is much simpler, and it removes the need for having the xml file etc.

To run it:

$ ./complexping 
Ask your question: rect=
Setting rect...
Ask your question: rect
width:  200  height:  200
Ask your question: 

