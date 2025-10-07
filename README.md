# real-estate-crm
This project is for simply show how to run react on local host step by step
Your environment has been set up for using Node.js 22.15.0 (x64) and npm.

C:\Users\admin>npm install create-react-app -g
npm warn deprecated inflight@1.0.6: This module is not supported, and leaks memory. Do not use it. Check out lru-cache if you want a good and tested way to coalesce async requests by a key value, which is much more comprehensive and powerful.
npm warn deprecated fstream-ignore@1.0.5: This package is no longer supported.
npm warn deprecated uid-number@0.0.6: This package is no longer supported.
npm warn deprecated rimraf@2.7.1: Rimraf versions prior to v4 are no longer supported
npm warn deprecated glob@7.2.3: Glob versions prior to v9 are no longer supported
npm warn deprecated fstream@1.0.12: This package is no longer supported.
npm warn deprecated tar@2.2.2: This version of tar is no longer supported, and will not receive security updates. Please upgrade asap.

changed 64 packages in 7s

4 packages are looking for funding
  run `npm fund` for details

C:\Users\admin>d:

D:\>md React_Demo

D:\>cd React_Demo

D:\React_Demo>create-react-app demo_project
create-react-app is deprecated.

You can find a list of up-to-date React frameworks on react.dev
For more info see:https://react.dev/link/cra

This error message will only be shown once per install.

Creating a new React app in D:\React_Demo\demo_project.

Installing packages. This might take a couple of minutes.
Installing react, react-dom, and react-scripts with cra-template...


added 1324 packages in 4m

270 packages are looking for funding
  run `npm fund` for details
Git repo not initialized Error: Command failed: git --version
    at genericNodeError (node:internal/errors:983:15)
    at wrappedFn (node:internal/errors:537:14)
    at checkExecSyncError (node:child_process:882:11)
    at execSync (node:child_process:954:15)
    at tryGitInit (D:\React_Demo\demo_project\node_modules\react-scripts\scripts\init.js:46:5)
    at module.exports (D:\React_Demo\demo_project\node_modules\react-scripts\scripts\init.js:276:7)
    at [eval]:3:14
    at runScriptInThisContext (node:internal/vm:209:10)
    at node:internal/process/execution:449:12
    at [eval]-wrapper:6:24 {
  status: 1,
  signal: null,
  output: [ null, null, null ],
  pid: 8816,
  stdout: null,
  stderr: null
}

Installing template dependencies using npm...

added 17 packages, and changed 1 package in 34s

270 packages are looking for funding
  run `npm fund` for details
Removing template package using npm...


removed 1 package, and audited 1341 packages in 13s

270 packages are looking for funding
  run `npm fund` for details

9 vulnerabilities (3 moderate, 6 high)

To address all issues (including breaking changes), run:
  npm audit fix --force

Run `npm audit` for details.

Success! Created demo_project at D:\React_Demo\demo_project
Inside that directory, you can run several commands:

  npm start
    Starts the development server.

  npm run build
    Bundles the app into static files for production.

  npm test
    Starts the test runner.

  npm run eject
    Removes this tool and copies build dependencies, configuration files
    and scripts into the app directory. If you do this, you can’t go back!

We suggest that you begin by typing:

  cd demo_project
  npm start

Happy hacking!

D:\React_Demo>cd demo_project

D:\React_Demo\demo_project>npm start

> demo_project@0.1.0 start
> react-scripts start

(node:2580) [DEP_WEBPACK_DEV_SERVER_ON_AFTER_SETUP_MIDDLEWARE] DeprecationWarning: 'onAfterSetupMiddleware' option is deprecated. Please use the 'setupMiddlewares' option.
(Use `node --trace-deprecation ...` to show where the warning was created)
(node:2580) [DEP_WEBPACK_DEV_SERVER_ON_BEFORE_SETUP_MIDDLEWARE] DeprecationWarning: 'onBeforeSetupMiddleware' option is deprecated. Please use the 'setupMiddlewares' option.
Starting the development server...
Compiled successfully!

You can now view demo_project in the browser.

  Local:            http://localhost:3000
  On Your Network:  http://172.16.69.19:3000

Note that the development build is not optimized.
To create a production build, use npm run build.

webpack compiled successfully

