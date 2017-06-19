# Ship-It
Program to track different parcels, letters and shipments across several tracking API providers.

## Planned Tracking Providers
I would like the program to allow tracking for the most common tracking providers across Central Europe and the USA/Canada:
- DHL
- FedEx
- UPS
- GLS
- Deutsche Post Mail
- DPD
- Hermes

Suggestions for additional providers and their trackers are welcome.

## Technology
In order to make this program available for Android, iOS and Windows with a common code base on C#, this project will use the **Xamarin Framework**.

## Related Downloads
[Visual Studio 2017](https://www.visualstudio.com/vs/)

[Visual Studio 2017 for Mac](https://www.visualstudio.com/vs/visual-studio-mac/)

## Extensions
In order to make sure that everyone can participate and contribute effectively, please install the following Visual Studio Extensions from the VS 2017 menu (go to _Tools_ -> _Extensions and Updates..._):
- Web Essentials 2017 ([More information](https://github.com/madskristensen/WebEssentials2017))
- Productivity Power Tools 2017 ([More information](https://marketplace.visualstudio.com/items?itemName=VisualStudioProductTeam.ProductivityPowerPack2017))

## Branching
Work will be done mainly on the _master_ branch, new tracking providers will be initially added on a _feature_ branch that will be merged into the master branch after review.

## Coding Guidelines
### Indentations
- Use tabs, not spaces.
- Please make sure you tabify your work before submitting it.

### Names
- Use PascalCase for `functions`, `methods`, `properties`, `constants` and `class` names.
- Use camelCase for `variables`, `enum` values and `local variables`.
- Use while words when naming, and make method names describe the use.

### Annotations
- Use // comments regularly and describe the code in a concise and professional manner.
- Use /// summaries to describe your methods and functions in one or two sentences.

### Style
- Always surround loops and conditional bodies with curly braces.
- Curly braces have their own line.
