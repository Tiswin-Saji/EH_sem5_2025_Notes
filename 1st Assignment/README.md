# Assignment 1

Assignment : Serve a Directory using Python

Use python3 -m http.server 8080 in a directory.

-------

# Overview

Python 3 comes with a built-in HTTP server that can be used to serve the files in a directory. To start the server the command 

`python3 -m http.server 8080`

can be used. This will serve the files in the directory from which python was invoked. To change the directory, the `cd` command can be used in PowerShell, to move to the desired directory.
In this command the argument `8080` refers to the port on which the HTTP server will be running and can be replaced with any other unused port on the system.

# Tools Required

Python 3

# Running the HTTP server

On Windows, the HTTP server can be started by running the command `python3 -m http.server 8080` in Windows Terminal (this requires that the python executable is added to the PATH).

<img width="681" height="119" alt="image" src="https://github.com/user-attachments/assets/f70a8863-c119-46ca-884f-5d8e78a20108" />

The server can now be accessed by navigating to `localhost:8080` (replace 8080 with the port chosen) in the browser.

<img width="1920" height="1020" alt="image" src="https://github.com/user-attachments/assets/635c92e2-8c83-4f68-afce-c7e024fd47fc" />

Clicking on a file will download the file in the browser.

# Stopping the HTTP server

The server can be stopped by issuing CTRL-C in the terminal causing the program to terminate.

# Conclusion

In this assignment a simple file browser was implemented using Python's built-in HTTP server. Moreover we also saw how to customize the port used by Python for the HTTP server.
