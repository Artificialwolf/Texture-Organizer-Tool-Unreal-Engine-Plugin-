# Texture-Organizer-Tool-Unreal-Engine-Plugin-
Texture Organizer Tool is an Unreal Engine editor plugin that automatically organizes textures based on their resolution. It helps artists and technical artists manage large texture libraries quickly and efficiently.
Features

• Automatically detects texture resolution
• Organizes textures into resolution-based folders
• Batch processing for large texture libraries
• Simple and easy-to-use UI
• Helps maintain clean and organized projects
• Designed for artists and technical artists

Example

Source folder:

Textures
T_Wood_D (1024)
T_Rock_D (2048)
T_Grass_D (512)

After running the tool:

SortedTextures
 512
   T_Grass_D
 1024
   T_Wood_D
 2048
   T_Rock_D

Textures are automatically moved into the correct resolution folder.

Installation

Download the plugin.

Copy the plugin folder into your Unreal project:

YourProject
 └ Plugins
     └ TextureOrganizer

Restart Unreal Engine.

Enable the plugin from:

Edit → Plugins
Usage

Open the Texture Organizer Tool UI.

Enter the Source Folder path and select all texture.

Enter the Target Folder where sorted textures will be placed.

Click Organize.

The tool will automatically create resolution folders and move textures accordingly.

Use Cases

• Organizing large texture libraries
• Cleaning up marketplace asset packs
• Managing textures in large Unreal projects
• Pipeline automation for technical artists

Technologies Used

• Unreal Engine
• Unreal Python API
• Editor Utility Widgets
• Blueprint to Python automation
