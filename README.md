# Ignia Website Structure

As Ignia collaborates with a variety of developers, having a consistent, predictable organizational structure for projects is critical. This project establishes the baseline directory structure for all Ignia projects.

> *Note:* Particular *types* of projects, such as AngularJS or Microsoft MVC applications, will expand upon this foundation; this will typically be done as part of a boilerplate project.

## Website Structure
Each website will have the following basic folder structure:
- [x] [Images](./Static/Images/)
  - [ ] Layout
  - [ ] Photos
  - [ ] Icons
- [x] [Shared](./Static/Shared/)
  - [x] [Fonts](./Static/Shared/Fonts/)
  - [x] [Scripts](./Static/Shared/Scripts/)
    - [ ] [Vendor](./Static/Shared/Scripts/Vendor/)
  - [x] [Styles](./Static/Shared/Styles/)
- [x] [Views](./Static/Views/)
  - [x] [Shared](./Static/Views/Shared/)

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
- [x] [Static](./Static/)

<small>*Ignia is a registered trademark of Ignia, LLC*</small>
