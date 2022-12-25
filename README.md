# DraperDanMan.PackageTemplate

An empty package that contains stubbed files and folders of a Unity Package Manager (UPM) Package, to provide a template starting point for new packages.

## Documentation

See the official unity documentation on Packages here:
https://docs.unity3d.com/Manual/CustomPackages.html

## Package Details

Contains the package layout described in the docs:
```
<root>
  ├── package.json
  ├── README.md
  ├── CHANGELOG.md
  ├── LICENSE.md
  ├── Third Party Notices.md
  ├── Editor
  │   ├── [company-name].[package-name].Editor.asmdef
  │   └── EditorExample.cs
  ├── Runtime
  │   ├── [company-name].[package-name].asmdef
  │   └── RuntimeExample.cs
  ├── Tests
  │   ├── Editor
  │   │   ├── [company-name].[package-name].Editor.Tests.asmdef
  │   │   └── EditorExampleTest.cs
  │   └── Runtime
  │        ├── [company-name].[package-name].Tests.asmdef
  │        └── RuntimeExampleTest.cs
  ├── Samples~
  │        ├── SampleFolder1
  │        ├── SampleFolder2
  │        └── ...
  └── Documentation~
       └── [package-name].md
```

## Known Issues

- The template could contain more of the package.json options for customizing package details. 
- The documentation doesn't have a site-layout template yet.

## Licensing

MIT License Copyright © 2022 Daniel Draper

For licensing details see [LICENSE.md](LICENSE.md)