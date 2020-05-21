# Angular: Getting Started

All notes and code based on the work done by [Deborah Kurata](https://app.pluralsight.com/profile/author/deborah-kurata)

* https://www.pluralsight.com/courses/angular-2-getting-started-update
* https://blogs.msmvps.com/deborahk/angular-2-getting-started-problem-solver
* https://github.com/DeborahK/Angular-GettingStarted
* https://www.typescriptlang.org/play
* https://www.npmjs.com/~angular

### Setup

Install the tools needed.

* Editor [Visual Studio (VS) Code](https://code.visualstudio.com/) is recommend
* NPM (Node Package Manager) which is the online registry of packages
* Cannot install NPM directly, you have to install [Node](https://nodejs.org/en/download) which will pull down NPM for you

### NPM

Examples use from command line

```
// this will install `Bootstrap` into a subfolder called `node_modules`
npm install Bootstrap

// Check version, angular needs >= 6.11
npm -v
```

To restore the packages in your `package.json` file

```
C:\Dev\angular-2-getting-started-update\Angular-GettingStarted\APM>

npm install
```

Run the app using the `package.json` in the `scripts` area, running `start` actually runs `ng serve -o`

```
npm start
```



