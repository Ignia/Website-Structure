# Ignia Website Structure

As Ignia collaborates with a variety of developers, having a consistent, predictable organizational structure for projects is critical. This project establishes the baseline directory structure for all Ignia projects.

> *Note:* Particular *types* of projects, such as AngularJS or Microsoft MVC applications, will expand upon this foundation; this will typically be done as part of a boilerplate project.

## Website Structure
Each website will have the following basic folder structure:
- [x] [Images](./Builds/Development/Images/)
  - [ ] Layout
  - [ ] Photos
  - [ ] Icons
- [x] [Shared](./Builds/Development/Shared/)
  - [x] [Fonts](./Builds/Development/Shared/Fonts/)
  - [x] [Scripts](./Builds/Development/Shared/Scripts/)
    - [ ] [Vendor](./Builds/Development/Shared/Scripts/Vendor/)
  - [x] [Styles](./Builds/Development/Shared/Styles/)
- [x] [Views](./Builds/Development/Views/)
  - [x] [Shared](./Builds/Development/Views/Shared/)

> *Note:* Checked items are expected to exist on every Ignia website.

## Build Structure
Most projects will be part of a build process, which provides the additional structure on top of the website structure:
- [x] [Builds](./Builds/)
  - [x] [Development](./Builds/Development/)
  - [x] [Production](./Builds/Production/)
- [x] [Source](./Source/)
  - [x] [Styles](./Source/Styles/)
  - [x] [Scripts](./Source/Scripts/)
  - [x] [Dependencies](./Source/Dependencies/)

<small>*Ignia is a registered trademark of Ignia, LLC*</small>
