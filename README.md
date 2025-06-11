# PDF Compressor v1 | https://www.abort.lol/


Self hosted GUI in HTML using NodeJS & GhostScript for fast & easy compression

Removes unnecessary data while preserving the file content's quality

Similar to Adobe Acrobat except it's free.

- Required Dependencies

NodeJS [download](https://nodejs.org/en
) | GhostScript [download](https://ghostscript.com/releases/gsdnld.html
) 10.05.1 for Windows (64 bit) Ghostscript AGPL Release

Install instructions below

https://github.com/user-attachments/assets/6dead109-25b9-4ae4-a1ed-73284d727949

After downloading required dependencies you may need to restart your computer

1 - Verify NodeJS is installed by running the following command;

node -v

2 - Verify GhostScript is installed by running the following command;

gswin64c -v

After confirming NodeJS and GhostScript are properly installed...

3 - Run the following command in CMD or PowerShell

npm install express multer@1.4.4 dayjs chalk@4 open

4 - Setup Complete!

Now run "start-server.bat" it will automatically startup the server also opening a new tab in your default browser to localhost:3000

Upload your PDF and compress then download!
Don't forget to close the server when you're done (CTRL + C)

...or alternatively (but NOT recommended) you can manually start
the server by running the following command; 

node server.js

(WARNING: This does NOT display the runetime or any server information in terminal! You also will need to manually open a new tab in your browser and navigate to localhost:3000)


Visit my website for more [abort.lol](https://www.abort.lol/
)
