cmpe239
=======

cmpe239 project - Real-time data analytics on energy consumption of IoT devices

How to Setup
============

[Disclaimer]
This application requires a device that is setup to the at&t m2x platform. 
Because of this, this application is a prototype and can only be used with
the intended device. The application will run without the device connection,
but no data will flow through the system.

Setup:
This application requires your system to have node.js installed. To do this
go to the nodejs.com website and install node on your machine.

Once node is installed, navigate in your console to the root directory.

Type:
npm install

this should install all the server dependencies. The application also requires
bower to be installed on the system.

Type:
npm install -g bower

Once installed...

Type:
bower install

Once these dependencies are installed on the system, you can run the application.
To do so...

Type:
node server.js

This will start the server. To see the application on your local machine open a
browser to

localhost:8000

[NOTE] - Please contact Jason/Divanshu <mrcruz86@gmail.com> <divanshu.arneja@gmail.com> to test the application with 
the device running.
