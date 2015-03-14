# Styles Directory

The location for any stylesheets associated with the site. This will typically include a single `Styles.css`, although it *may* include separate layout or theme files that are intended to be called on a per-page basis.

> *Note:* Stylesheets will typically be populated by the build process based on pre-processed files located in `/Source/Styles/`.

> *Note:* On occassion, stylesheets will be created for individual views, such as the homepage, that have unique styles. In these cases, these files should be compiled independent of the `Styles.css` and placed alongside their corresponding view file (e.g., in `/Views/_home.css`).