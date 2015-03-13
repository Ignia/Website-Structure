# Scripts Directory

Any pre-compiled JavaScript files will go in this directory. Eventually, this will be TypeScript files; until [TypeScript 2.0](http://www.typescriptlang.org/), however, this will typically be ECMAScript 6.0 files to be transpiled using [Babel](https://babeljs.io/) or [Google Traceur](https://github.com/google/traceur-compiler).

## Files
For Angular files, the `/Scripts` folder will typically be broken down into:
````
+- /Controllers
+- /Directives
+- /Services
````
For all other projects, the organization will vary by technologies used.


> *Note:* JavaScript files from vendors will typically be placed in the `/Source/Dependencies` folder.