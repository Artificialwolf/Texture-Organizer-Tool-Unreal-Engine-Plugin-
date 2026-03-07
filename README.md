<p align="center">
  <img src="https://img.shields.io/badge/Unreal%20Engine-5.1%2B-0E1128?style=for-the-badge&logo=unrealengine&logoColor=white" alt="UE Version" />
  <img src="https://img.shields.io/badge/Python-API-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python API" />
  <img src="https://img.shields.io/github/license/YOUR_USERNAME/Texture-Organizer-Tool?style=for-the-badge" alt="License" />
  <img src="https://img.shields.io/github/stars/YOUR_USERNAME/Texture-Organizer-Tool?style=for-the-badge" alt="Stars" />
  <img src="https://img.shields.io/github/downloads/YOUR_USERNAME/Texture-Organizer-Tool/total?style=for-the-badge" alt="Downloads" />
</p>

<h1 align="center">Texture Organizer Tool</h1>
<h3 align="center">Unreal Engine Editor Plugin – Auto-Organize Textures by Resolution</h3>

<p align="center">
  <strong>A must-have tool for artists and technical artists</strong> to keep massive texture libraries clean and organized in seconds.
</p>

<p align="center">
  <img src="https://via.placeholder.com/800x400/0E1128/FFFFFF?text=Texture+Organizer+UI+Screenshot" alt="Tool UI Screenshot" width="800"/>
  <br/>
  <em>Simple UI – Select folder → Click Organize → Done!</em>
</p>

## ✨ Features

- 🔍 **Auto-detects** texture resolutions (2K, 4K, 1K, 8K, custom, etc.)
- 📁 **Organizes** textures into smart resolution-based folders (e.g., `/Textures/4K/`, `/Textures/2K/`)
- ⚡ **Batch processing** – handles hundreds or thousands of textures quickly
- 🖼️ Clean, intuitive **Editor Utility Widget** UI
- 🚀 Built for **large projects**, marketplace assets, and production pipelines
- 🛠️ No more manual sorting – saves hours of work

<p align="center">
  <img src="https://via.placeholder.com/800x400/1A1F2E/FFFFFF?text=Before+→+After+Organization" alt="Before After Example" width="800"/>
  <br/>
  <em>Before: Messy folder → After: Perfectly sorted!</em>
</p>

## 📥 Installation

1. **Download** the latest release from [Releases](https://github.com/YOUR_USERNAME/Texture-Organizer-Tool/releases) (or clone the repo)
2. Copy the plugin folder into your project (or engine Plugins folder):

3. Restart Unreal Engine
4. Go to **Edit → Plugins**, search "Texture Organizer" and **enable** it
5. Restart the editor again (sometimes needed for Editor Utility Widgets)

> **Recommended**: Install per-project (in `YourProject/Plugins/`) so team members get it automatically with version control.

## 🚀 Usage

1. In Unreal Editor, go to **Tools → Texture Organizer** (or your custom shortcut)
2. The Editor Utility Widget opens
3. **Right-click** the widget → **Run** (or use the button)
4. Set:
- **Source Folder**: Where your unsorted textures are
- **Target Folder**: Where sorted subfolders will be created (can be same as source)
5. Select textures (or all in folder)
6. Click **Organize**
7. Watch it create folders like `4K/`, `2K/`, `8K/` and move files automatically!

> Tip: Works best with **Content Browser** multi-select or folder drag-drop.

## 🎯 Use Cases

- Cleaning up messy **marketplace asset packs**
- Organizing **photogrammetry / scanned textures** libraries
- Maintaining clean structure in **AAA-scale projects**
- Automating texture pipelines for **technical artists**
- Preparing assets before packaging / cooking

## 🛠️ Built With

- Unreal Engine **Editor Utility Widgets**
- **Unreal Python API** (for fast file operations)
- **Blueprint-Python** hybrid automation
- Zero external dependencies – pure UE + Python

## ⚙️ Compatibility

- Unreal Engine **5.0 – 5.5+** (tested up to latest)
- Windows (primary), Linux/Mac possible with minor tweaks

## 🤝 Contributing

Pull requests welcome! Especially:

- Support for more resolution patterns
- Dry-run / preview mode
- Custom folder naming rules
- Performance optimizations for 10,000+ textures

1. Fork the repo
2. Create feature branch (`git checkout -b feature/amazing-feature`)
3. Commit (`git commit -m 'Add amazing feature'`)
4. Push (`git push origin feature/amazing-feature`)
5. Open Pull Request

## 📄 License

Distributed under the MIT License. See [`LICENSE`](LICENSE) for more information.

## 💬 Contact / Support

- GitHub Issues → for bugs & feature requests
-Discord  → 

---

<p align="center">
Made with ❤️ for the Unreal community • Star ⭐ if it helps your workflow!
</p>
