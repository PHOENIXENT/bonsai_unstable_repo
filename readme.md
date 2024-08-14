### Bonsai daily builds with in-blender autoupdate

Only supported for Bonsai with Python 3.11 (default Python version in Blender 4.2+) as Blender doesn't support separate builds for different Python versions.

1. Setup Bonsai Daily Builds Repository.

Drag'n'drop url for your platform from the table below to Blender, accept adding a new repository.

![](img/image-1.png)

During repository creation check "Check Updates On Startup" to get updates for daily Bonsai builds automatically.

![](img/image-2.png)

Alternatively, repository can be created manually, without drag'n'drop:

- Open Blender Preferences -> "+" -> "Add Remote Remository". You'll see a window similar to the one above.

- Use as URL: `https://raw.githubusercontent.com/IfcOpenShell/bonsai_unstable_repo/main/index.json` and check auto-updates if you want them.



2. Install extension.

To install the Bonsai extension you can either drag'n'drop the same url again and install it:

![alt text](img/image-3.png)

Or you can search for "bonsai" in Extensions and Install it.

![](img/image.png)


3. Each time you start Blender it will check for updates and you will be able to update BlederBIM using "Update" button.

![](img/image-4.png)

Make sure to restart Blender after.

![](img/image-5.png)


### Available daily builds




Blender Extensions


Blender Extension Listing:


Add\-on




---




| ID | Name | Description | Website | Blender Versions | Platforms | Size |
| --- | --- | --- | --- | --- | --- | --- |
| [bonsai\-0\.7\.11\-alpha240814](https://github.com/IfcOpenShell/IfcOpenShell/releases/download/bonsai-0.7.11-alpha240814/bonsai_py311-0.7.11-alpha240814-macos-x64.zip?repository=https://raw.githubusercontent.com/IfcOpenShell/bonsai_unstable_repo/main/index.json&blender_version_min=4.2.0&platforms=macos-x64) | Bonsai | A native Building Information Model authoring platform using IFC | [link](https://bonsaibim.org/) | 4\.2\.0 \- \~ | macos\-x64 | 89\.6MB |
| [bonsai\-0\.7\.11\-alpha240814](https://github.com/IfcOpenShell/IfcOpenShell/releases/download/bonsai-0.7.11-alpha240814/bonsai_py311-0.7.11-alpha240814-macos-arm64.zip?repository=https://raw.githubusercontent.com/IfcOpenShell/bonsai_unstable_repo/main/index.json&blender_version_min=4.2.0&platforms=macos-arm64) | Bonsai | A native Building Information Model authoring platform using IFC | [link](https://bonsaibim.org/) | 4\.2\.0 \- \~ | macos\-arm64 | 88\.9MB |
| [bonsai\-0\.7\.11\-alpha240814](https://github.com/IfcOpenShell/IfcOpenShell/releases/download/bonsai-0.7.11-alpha240814/bonsai_py311-0.7.11-alpha240814-linux-x64.zip?repository=https://raw.githubusercontent.com/IfcOpenShell/bonsai_unstable_repo/main/index.json&blender_version_min=4.2.0&platforms=linux-x64) | Bonsai | A native Building Information Model authoring platform using IFC | [link](https://bonsaibim.org/) | 4\.2\.0 \- \~ | linux\-x64 | 95\.8MB |
| [bonsai\-0\.7\.11\-alpha240814](https://github.com/IfcOpenShell/IfcOpenShell/releases/download/bonsai-0.7.11-alpha240814/bonsai_py311-0.7.11-alpha240814-windows-x64.zip?repository=https://raw.githubusercontent.com/IfcOpenShell/bonsai_unstable_repo/main/index.json&blender_version_min=4.2.0&platforms=windows-x64) | Bonsai | A native Building Information Model authoring platform using IFC | [link](https://bonsaibim.org/) | 4\.2\.0 \- \~ | windows\-x64 | 70\.7MB |


Built 2024\-08\-14, 07:59




