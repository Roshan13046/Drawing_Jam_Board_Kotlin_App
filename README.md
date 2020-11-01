# Kotlin Drawing App
This is a drawing app made for creating amazing drawings with exicting features of coloring, saving, editing, erasing, sharing, etc.

![drawingApp](https://user-images.githubusercontent.com/55108788/97798820-bf281000-1c4f-11eb-9eff-f936afa4da6e.png)

This Project is made as a part of Learning  Web Development. 

This webpage is made right from scratch to learn Node.js.
<b>Tools: Android, Git, Kotlin</b>

If you find any issues with the currently present implementations, feel to correct them or create an issue mentioning those.

## Project Description

● Developed as a Android application
● Architected using the Kotlin and Java
● It has multiple directories to store data and describe their size and last modified date and time and show data with their extensions.
● It has a feature to sort or reorder files and folders data on basis of name,size and lastmodified date.
● It also shows the path directory relative to the home directory and it's build using pure node.js without using any frameworks.
● I have also built in node modules of https to create server,child processors module,Path module,file system module

# Functionalities of App:

The different functionalities of my app are as follows

●There is a landing page for my app, when the users land on this page they can see different files and folders located in a directory chosen in the server.

●They can explore different folders and read the files inside them.

●The files have names, extensions, size, last modified date, and time.

●It also has a header at the top showing the full path of the file relative to the home directory which is the location of the directory chosen in the server.

●The directory home is like a static folder with static contents which we are serving to our user.

●If the user clicks on a folder and then clicks on a file inside it then the server is supposed to serve that file and the browser will be requested or required to read the file.

●If the browser is capable of reading the extension of the file or that type of file then is going to read it successfully.
for eg: If you click on the images then it will pop up a screen showing the images.
The same is the case with the media files like songs, videos, etc

●I have used readable file streams a very important feature of the node.js.

●On clicking on any of the full path links it will take you to that directory.

●It can use the correct dependencies of the files including js, CSS, HTML, etc.

●Another important feature of this app is that the user can reorder or sort the files and folders based on name, size, last modify date, and time.

●I have used a wide range of built-in node modules one of them is 
HTTP to create the server and use it to accept user requests and respond to them.

●I have also used the https module which is the HTTP protocol over tls SSL. This is used to get the JSON data from an external link that uses https.

●I have also used the child processors module which is also a built-in module in node. This module helps to run shell commands directly from node code. The shell's commands were also used to get the size of the directories.

●Another module I have used is the <b>path module </b>. It helps to manipulate the path easily without having to worry too much about how to resolve or concatenate paths as this module comes with strong features designed mainly for that purpose and it's used to read files using their path.
The path was a very important feature of this project.

●Another module I have used is the <b>file system module</b> which not only helps to read data to the server and passes to the ATP response but also helps to create readable streams.
for eg: when the user is streaming videos we require to create a readable stream meaning we will be sending chunks of data to the user instead of sending the whole file. So these streams send small chunks of data to the HTTP response to reduce memory usage.
This helps a lot especially with large files like videos.

## Learnings from above Project :


●Learned to use the child processors module, path module, file system module.
●Creating the server.
●Decoding the pathname and converting it to a full static path.
●Display folder content and print the title.
●Show the path inside a "Breadcrumb".
●Loop through folder elements.
●Print Icons- Get introduced to the child_process module.
●Calculate the size of the files.
●Get the mime type of files.
●Serve files to the client.
●Serve pdf files on the browser- serve the media content in chunks using a stream.
●Reorder the folder elements by name.
●Sort elements by size and last modified.
●Fixing project bugs.
●Deploying the app to Heroku. 



## Project Link: 

Check [Project] (https://my-file-explorer-by-roshan.herokuapp.com/)


## Contributions

Read the [Contribution Guidlines](https://github.com/Roshan13046/Online-File-Explorer-WebApp/blob/master/CONTRIBUTING.md) before you contribute.

You can also create an issue or [contact us](https://github.com/Roshan13046) if you have any doubts.


