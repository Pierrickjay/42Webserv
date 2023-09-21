# 42Webserv
Project of 42 common core. The project has been realized by Pjay and Rertzer.

If you want to compile it you need to change every path in the .conf file. Replace it with your root to the www folder.

You need to have gcc and make installed in your system.
When everything is installed you can do a make in the project root.
Then launch the ./webserv executable. If you want to test your own .conf file you can add it after the executable.
You will now see that the serv is running. You can now connect in GOOGLE CHROME(yes it's important, not every browser have the same behavior) : localhost:8080.
There are 4 differents server connected to 4 differents ports : 8080, 8081, 8083, 8084.
Each server have his own configuration. For example, in the port 8080 you can execute cgi because we defined it in the location /php. In the port 8081, you can make a delete request to the location /img/toDelete/$(thefilehere).

Have fun !


