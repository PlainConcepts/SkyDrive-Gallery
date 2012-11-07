Steps to install:
1. Create a Microsoft ID
2. Go to Live Connect Developer Center (http://msdn.microsoft.com/en-us/live/ff519582.aspx) and user your Microsoft ID credentials
3. Select "My Apps" and create one
4. In the settings specify the "Redirect domain" where the gallery is going to be. Ex.: http://mydomain.com
5. Open the file js/gallery.js and update the field "REDIRECT_URL" with the domain plus the path where the gallery is going to be published. For example, if the domain is http://mygallery.com and it is going to be published in http://mygallery.com/gallery  in the js file the value will be REDIRECT_URL="http://www.cascadiajs.com/gallery"
6. Update your server with the gallery

Final Note:
Once a user is authenticated, it will look for the folder "galleryFolder" to retrieve the pictures. If you want to change that path you just have to update the value of directoryName in js/gallery.js


