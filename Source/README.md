# Source Directory

Any files that *require* compilation (e.g., via a build process) will go in the `/Source` directory. This commonly includes pre-processed CSS (e.g., Sass or Less) and pre-compiled JavaScript (e.g., TypeScript, AtScript, or ECMAScript 6.0 files).

> *Note:* Files that are usable in a development build "as is" but go through additional processing for a production build (e.g., minification, obscufication) can be placed directly in the `/Builds/Development` directory.