# iTween
[![openupm](https://img.shields.io/npm/v/com.pixelplacement.itween?label=openupm&registry_uri=https://package.openupm.com)](https://openupm.com/packages/com.pixelplacement.itween/)

iTween is a battle-tested tweening and interpolation solution for Unity, used by well-known studios
like Square-Enix.

For complete documentation, examples, information or reporting any kind of bugs/comments/suggestions
visit [itween.pixelplacement.com](http://itween.pixelplacement.com)

This Unity package is maintained by **@itsjavi** in Github:
[github.com/itsjavi/iTween-Unity](https://github.com/itsjavi/iTween-Unity)

Licensed under the MIT License.

## Installation

### Install via OpenUPM

The package is available on the [openupm registry](https://openupm.com). It's recommended to install it via [openupm-cli](https://github.com/openupm/openupm-cli).


```
openupm add com.pixelplacement.itween
```

### Install via git URL

To install this package, you need to edit your Unity project's `Packages/manifest.json` and add this repository as a dependency. You can also specify the commit hash or tag like this:

```json
{
  "dependencies": {
    "com.pixelplacement.itween": "https://github.com/itsjavi/iTween-Unity#1.0.0",
   }
}
```

## About this repository

If you need the latest updates, you can also install the plugin using the
[official Asset Store plugin](https://assetstore.unity.com/packages/tools/animation/itween-84).

The `iTween.cs` is provided as-it-is, unchanged from the official project,
but this repository may add new C# scripts to complement or extend it features.

This repository uses SemVer tag versioning. The SemVer releases and tags of this repository
only represents the Unity package version and not the `iTween.cs` library version.
