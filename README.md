# OpenFlight Library

## What is it?
OpenFlight aims to be an open-source tool for distributing free Flight Simulator Addons and providing creators with an update utility allowing them to provide users with OTA updates with minimal configuration after initial release.

## Languages and Framework
I plan on developing the application using JVM (mainly because I know Java very well and Kotlin to some extent) with UIs provided by JavaFX (with extensions to make it look better). 

The Primary Language will be Java with some Kotlin to supplement (if you wish, you may use another JVM language to develop a feature)

## Processes
### Auto Update
The system will come with an Update Service which can be toggled to launch at boot or through manual activation to check for and download updates.
### Library
The Library feature will allow users to view and download addons into their flight simulator. This data is fetched from online repositories. By default, the OpenFlight repository will be installed but additional repositories and repo-groups can be added.
#### OpenFlight Repository
An open github organisation will be used to host repositories from creators. These repositories are linked to another opensource git repository hosted on Github (Support on additional git platforms and CDNs may come in the future). Each repository must have at least 10 GitHub Stars before they are added to the organisation page. The owner of that repository, will have admin access to the corresponding OpenFlight repository. This repository will hold information regarding the addon, additional information, configurators.

### Configurators
The Application will come built with an API that allows developers to implement addon configurators directly into the System rather than having to build one from the ground up

### Customisable Launcher
The application will come with support for starting specific addon-external processes when the flight simulator is launched if required

## Supported Flight Simulators

| Simulator      | Support Level |
| ----------- | ----------- |
| Microsoft Flight Simulator      | Main Title APIs Designed to accomodate as primary target       |
| Prepar3D   | Full Support for P3D addon manager systems and most APIs        |
| X-Plane | TBC |
| FSX |  TBC |


