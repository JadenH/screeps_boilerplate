# Screeps Boilerplate
### About
This is a starter with Grunt and hot reload. On file saves, it will auto update on Screeps.

### Config
A config.json is required in the root of the project:
```json
{
  "branch": "dev",
  "email": "blah@gmail.com",
  "password": "screeps_password",
  "ptr": false,
  "private_directory": true,
  "host": "localhost",
  "port": 21025,
  "http": true
}
```

### Running
1. `npm install` to install required packaged
2. `npm i -g grunt` to install [Grunt](https://gruntjs.com/) globally.
3. This utilizes [Screeps Mod Auth](https://www.npmjs.com/package/screepsmod-auth). Setup an email and password through your screeps server.
4. Create a [config file](#config)
5. `Grunt Watch` or run the run.bat (run.sh) to start

### Building your AI
1. Start writing in loop.js in the src directory.
2. Don't modify main.js or version.js!
3. To create more than a single javascript file, use [import](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/import)
