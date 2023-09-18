
# [Adir Landes Portfolio](durrlanders.org)
Built with Astro
### Adding new Images

##### 1. Clone the repository locally.
> git clone https://github.com/liamtsang/durrlanders.git

##### 2. Navigate to the image folders and add in your images with the name [x].jpg.

> /

> ├── public/

> │   ├── images/

> │   │   └── **desktop**/

> │   │   └── **mobile**/

##### 3. Add the route to the pictures in the desktopImages and mobileImages arrays inside the Index.astro file.
> /

> ├── src/

> │   ├── pages/

> │   │   └── **index.astro**

>e.g "images/desktop/8.jpg", and "images/mobile/8.jpg",

##### 4. Push changes to GitHub using these commands. (let me know if you have trouble with this I can help)

> git add .

> git commit -m "new images"

> git push

##### 5. Login in to DigitalOcean and open the Droplet, then select Access. Hit "Launch Droplet Console" - this should open up a CMD prompt.
##### 6. Once the prompt is open, use these commands:

>cd &#46;&#46;/srv/www/durrlanders

>git pull

>npm run build

>sudo service nginx restart


##### 7. And everything should be updated!