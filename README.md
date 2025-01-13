# Simple NPM web project setup

This is an example how to use Node.js and NPM to develop a vanilla js web app. You can create your website with all desired NPM packaged in the `./src` folder.

To start this project run the following command in the root folder of the project.

```bash
npm install
```

The follwoing command will start a local server. That way you can see your changes live.

```bash
npm run dev
```

If you want to deploy your website to a hosting provider, please run the following command.

```bash
npm run build
```

This will build your website in the `./dist` folder. You can take the files from this folder and move them to a static hosting.

This is how to create a website with npm packages and deploy it to production.
