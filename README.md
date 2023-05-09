# 🕹️ Synthetic data generator

### 📁 Table of Contents

* <a href="#general">General</a>
* <a href="#requirements">Requirements</a>
    * <a href="#collections-and-plugins">Collections and plugins</a>
    * <a href="#expected-tree">Expected tree</a>
* <a href="#configuration">Configuration</a>
* <a href="#contributors">Contributors</a>

### 🏙️ General

This repository generates __synthetic data of Paris__ from [OpenStreetMap](https://www.openstreetmap.org) data and animates it with the [City Sample](https://www.unrealengine.com/marketplace/en-US/product/city-sample) project (pedestrians, cars). 
The synthetic data is captured in several formats (RGB and semantic).<br/>

The objective is to detect AI models biases from this synthetic data. For instance, detect if our crowd counting model is efficient either day and night by submitting two datasets.

### 🧰 Requirements

- [Unreal Engine 5.1.1](https://www.unrealengine.com/fr/unreal-engine-5)

#### Collections and plugins

In your project, you will need to add:

- [City Sample Crowds](https://www.unrealengine.com/marketplace/en-US/product/city-sample-crowds)
- [City Sample Vehicles](https://www.unrealengine.com/marketplace/en-US/product/city-sample-vehicles)

#### Expected tree

```bash
. [Twincity]
└── Content # Download from the marketplace 👇
  └── City Sample Crowds
  └── City Sample Vehicles
├── [...]
└── Plugins # Create a Plugins folder where you can clone EasySynth repository 👇
    └── EasySynth
```

### 👋 Contributors

- Lead Dev - [Jehanne Dussert](https://github.com/JehanneDussert/)
- Dev - [Rémi Giner](https://github.com/remisansfamine/)
- Dev - [Nobila Traore](https://github.com/notraore/)
- Game Artist - [William Lahemar](https://github.com/willocks)
