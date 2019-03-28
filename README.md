# Example of initial delay of main task REST server (using electron-quick-start as basis for this project)

This is a small example that started with the electron-quick-start project.  It demonstrates starting an Express REST server in the main process that responds to a 'test' message that the renderer process calls.

Upon start-up, there's a 20 second delay before the REST interface is ready and accepts a GET request from the renderer process.

If you wait 10 seconds before sending the message (using the onscreen button), then the delay is about 10 seconds.  If you wait more than 20 seconds, there's no appreciable delay.

