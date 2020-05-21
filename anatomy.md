| Name                            | Description                                                  |
| ------------------------------- | ------------------------------------------------------------ |
| Application                     | Made up of components                                        |
| Services & Dependency Injection | Provide functionality across components                      |
| Component                       | Template (View), Class (Code for the view, properties and methods), Metadata (Provides information to Angular) |
| Modules                         | Groups components into cohesive blocks of functionality.     |
| ES Modules                      | Code files that import or export `things`. These organize our code files. Modularize our code. Promote code reuse. |
| Angular Modules                 | Code files that organize the application into cohesive blocks of functionality. Organize our application. Modularize our application. Promote application boundaries. |
| Templates                       | View layout fragment, created with HTML, includes Angular binding and directives in the HTML |
| Template resolution environment | When the Angular Compiler see's a directive like `<pm-root></pm-root>` in a template it looks to the Angular Module for the definition. This is under `declarations` |
| Interpolation                   |                                                              |
| Directives                      |                                                              |
| Databinding                     | Renders property valules from the class in the HTML<br /><br />EG: `<h1>{{pageTitle}}</h1>` |
| Pipes                           |                                                              |
| Retrieve Data Using HTTP        |                                                              |
| Navigation                      |                                                              |
| Routing                         |                                                              |
| CLI (Command Line Interface)    |                                                              |
| Transpiled                      | New JS (JavaScript) features in code must be compiled by a tool that converts the new JS syntax (ES2015) to comprable older syntax the browser can understand. |
| TypeScript                      | Strongly typed and Open source super set of JavaScript developed by Microsoft. TypeScript transpiles to JavaScript. |
| ES2015                          | Is Class-based object-orientated, allows for interfaces and inheritance. |
| package.json                    | Stores dependencies (libruarys/packages) that your application needs to run, NPM will download and install these to `node_modules` |
| Lazy Load                       |                                                              |
| Load on start                   |                                                              |
| Decorator                       | Used to define MetaData on a component. Its a function that adds MetaData to a class, its members or its method arguments.<br /><br />EG: `@Component({ })`<br />EG: `@NgModule({ })` |
| MetaData                        | Provides extra data for Angular, the metadata defines the class as an Angular component. |
| selector                        | Defines the components directive name, the perfix **pm** relates to your project. The examples from [Deborah Kurata](https://app.pluralsight.com/profile/author/deborah-kurata) was for a Product Manger, so she used **pm**.<br /><br />EG: `selector: 'pm-root'` |
| directive name                  | Custom HTML tag, this is the name used to inject the component template into the  HTML<br /><br />EG: `<pm-root></pm-root>` |
| Angular Compiler                | ~~JIT (Just in time compiler)~~, depricated in Angular V9    |
| Angular Compiler                | Ahead of Time compiler (AOT), used during development, pre-compiles before serving. From V9 used for deployment, pre-compiles before deploying.<br /><br />Terminal window (Editor) is the source of truth for **compile** related errors. |
| Bootstrapping                   | Self starting process that loads and goes                    |

