# Scripts Directory

The location for any JavaScript files associated with the site. This will typically include a single `Script.js`, which is a concatenated version of all source files, although it *may* include separate libraries that are only intended for use on particular pages.

> *Note:* JavaScript files will typically be populated by the build process based on pre-processed files located in `/Source/Scripts`.

> *Note:* On occassion, JavaScript files will be created for individual views, such as the homepage. In these cases, the files should be compiled independent of the `Scripts.js` file and placed next to their corresponding view file (e.g., in `/Views/_home.js`). This includes AngularJS controllers that are view-specific.
