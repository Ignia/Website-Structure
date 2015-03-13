# Builds Directory

Location of compiled or post-processed files. For Ignia's standard build process, this includes `Development` and `Production`.

> *Note:* When working with .NET projects in Visual Studio, this requires retargeting the default `Debug` and `Release` folders.

> *Note:* For most web-development projects, files not requiring pre-processing for the development build will be stored natively in the `Development` folder. These will be copied to `Production` during the production build process. This includes files who need minification (e.g., HTML, images), but no additional post-processing.
