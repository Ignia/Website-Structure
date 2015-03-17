# Static Directory

This is the location for all files *not* requiring *precompilation*. This includes files that may be minified as part of a production build (e.g., HTML, JSON, images), but otherwise require no additional preprocessing; i.e., they could be served directly if needed.

> *Note:* This includes files that may be *dynamically compiled* or *preprocessed* by the server at *runtime* (e.g., ASP.NET files). These files may not traditionally be thought of as "static", but they are in context of the *build process*.