# Scoop Bucket

This is my personal [Scoop](https://scoop.sh/) bucket.

## Manifests

This bucket includes the following manifests:

| Manifest Name | Manifest File                                                                                        | GitHub Repository                                                                   |
|---------------|------------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------|
| `helium`      | [helium.json](https://github.com/fahim-ahmed05/scoop-bucket/blob/master/bucket/helium.json)          | [imputnet/helium](https://github.com/imputnet/helium)                               |
| `inter-font`  | [inter-font.json](https://github.com/fahim-ahmed05/scoop-bucket/blob/master/bucket/inter-font.json)  | [rsms/inter](https://github.com/rsms/inter)                                         |
| `vacuumtube`  | [vacuumtube.json](https://github.com/fahim-ahmed05/scoop-bucket/blob/master/bucket/vacuumtube.json)  | [shy1132/VacuumTube](https://github.com/shy1132/VacuumTube)                         |
| `clickpaste`  | [clickpaste.json](https://github.com/fahim-ahmed05/scoop-bucket/blob/master/bucket/clickpaste.json)  | [Collective-Software/ClickPaste](https://github.com/Collective-Software/ClickPaste) |

## Installation

To add this bucket and install apps from it, run the following PowerShell commands:

```pwsh
scoop bucket add <bucketname> https://github.com/fahim-ahmed05/scoop-bucket
scoop install <bucketname>/<manifestname>
```

Replace `<bucketname>` with your preferred local name for the bucket, and `<manifestname>` with the app you want to install.

## Contributing

Want to add or improve a manifest?  
Please read the following guides before submitting changes:

- [Contributing Guide](https://github.com/ScoopInstaller/.github/blob/main/.github/CONTRIBUTING.md)  
- [App Manifests Wiki](https://github.com/ScoopInstaller/Scoop/wiki/App-Manifests)

Pull requests are always welcome!

