# WinGet Configuration

This repository contains a collection of WinGet configuration files (`*.dsc.yaml`) that I use to manage settings and software on my machines with the Windows Package Manager.

For more information, see [WinGet Configuration](https://learn.microsoft.com/en-us/windows/package-manager/configuration/).

## Usage

Use the `winget configure` command:

```
> winget configure configuration.dsc.yaml
```

Or, open the configuration file in the [Dev Home](https://learn.microsoft.com/en-us/windows/dev-home/setup) app.

## Configuration Files

Configuration files are availabile in the `configurations/` directory, split into workload-specific categories.

| File | Description |
| ---- | ----------- |
| `configuration.dsc.yaml` | Default machine configuration.  Configures Windows settings and installs core tools. |
| `devtools.dsc.yaml` | Installs a collection of useful development tools. | 
| `visualstudio.dsc.yaml` | Installs Visual Studio with the C# and C++ workloads.  |
