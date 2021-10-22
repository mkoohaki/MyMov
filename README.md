# MYMOVIES
<img src="images/ProjectTree.JPG" width="250px" height="auto"><br>

MYMOVIES is a web application which is created in Visual Studio by using full-stack JavaScript solution.<br>
- This applicatoin comprises three major building blocks of 4 possible layers:<br>
   • MongoDB as the database<br>
   • Express as the web server framework<br>
   • Node.js as the server platform<br>
- This application can be used for selecting the favorites movies.<br>
- User signup indivisually or by Google account. He can complete the account by adding the photo as visual (application creates a local folder in public/imageStorage folderautomaticly and save the image there and also in the database, if user change it, application will delete the old image and if user delete the account, the folder will gone), for Google users application uses their photos from Google. Individual users should use valid email, activate code will send to their email address.<br>
- User can retrieving username, change password, delete account.<br>
- User can search his/her favorite movie by full name or part of that, application search in a rest API in http://www.omdbapi.com and return the result movies then user can save any of the titles. User can save maximum 5 titles, and the title can be deleted and add another instead, it displays the iformation includes title, director, runtime, year, and the poster. If user search and a title already save, then the save button in the search list would be changed to 'S a v e d' and it does not do anything by clicking.<br>
- The application shows the favorrite movies of all users in home page and users do not need to login for seeing.<br>
