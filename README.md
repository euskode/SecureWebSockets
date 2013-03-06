This project is meant to add working TLS support to the Autobahn WebSocket library as a preliminary step to implementation at work.

The problem being solved was in part switching the Autobahn library off of Java NIO. Java NIO is broken on Android and you must use the classic java sockets. [Android Issue 12955][1]

The project comes with an example WebSocket Echo client that communicates with [WebSocket.org's echo server][2] with or without SSL encryption.

[1]: http://code.google.com/p/android/issues/detail?id=12955
[2]: http://www.websocket.org/echo.html
