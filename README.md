Before doing this steps make sure you have a COMPOSER and Node.js installed.

#ZURB
[Zurb Guide](https://foundation.zurb.com/emails/docs/sass-guide.html)

##My cmd/folder location is wamp64/www/inky. It's an empty folder. We expect that you are running this command under that location.

1. We'll use the Foundation CLI to set up a new project. If you already have the Foundation CLI installed from Foundation for Sites, you can skip this first command.
```shell
  inky> $ npm install --global foundation-cli
```

2. (OPTIONAL) If you run into any permission errors (EACCESS) on OS X or Linux, you can try prefixing the command with `sudo`
```shell
  inky> $ sudo npm install --global foundation-cli
```

3. Once the CLI is installed on your machine, it’s super easy to fire up a blank Foundation for Emails project. 
Move into the folder you store your projects in, and then run this command:
```shell
  inky> $ foundation new --framework emails
```

4. After those 3 step it will ask you to create a folder for your inky emails, In my side I created lithios folder inside the inky folder.

##Running the Server
1.Change the cmd location to your project folder (example: cd lithios). Then start the server.
```shell
  inky\lithios>npm start
```

2. Folders will be created under the lithios project. Here's a breakdown of the files in the `src` folder:
-`assets/`: Sass and image files. <br />
-`layouts/`: Boilerplate HTML that wraps all of your emails. <br />
-`pages/`: HTML files for emails. <br />
-`partials/`: Reusable chunks of HTML that can be injected into pages <br />


3. `dist/`: Your HTML final output, included with the assetes(image and css). This is outside the `src` folder OR located in the root of your project folder name.

##Then you're good to go! Please check the Zurb link above for file structure and coding styles.