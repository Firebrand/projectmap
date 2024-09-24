# ProjectMap

ProjectMap is a Visual Studio Code extension that allows you to annotate your project's files and folders with custom annotations. This tool helps developers and teams maintain clear documentation about the structure and purpose of different parts of their codebase.

## Features

- **Project Tree View**: A custom tree view in the sidebar that displays your project structure.
- **File and Folder Annotations**: Add annotations to files and folders directly within VS Code.
- **Annotation Editor**: A dedicated webview for editing annotations.
- **Gitignore Integration**: Automatically respects your project's `.gitignore` file.
- **Auto-save**: Annotations are automatically saved as you type.

## Installation

1. Open Visual Studio Code
2. Go to the Extensions view (Ctrl+Shift+X)
3. Search for "ProjectMap"
4. Click Install

## Usage

### Viewing the Project Tree

1. After installation, you'll see a new "ProjectMap" icon in the Activity Bar.
2. Click on it to open the Project Tree view.

### Adding/Editing Annotations

1. In the Project Tree view, click on a file or folder.
2. The Annotation Editor will open, allowing you to add or edit the annotation.
3. Type your annotation in the text area.
4. The annotation will auto-save as you type.

### Opening Files

- Clicking on a file in the Project Tree will open it in the editor and allow you to edit its annotation.

### Commands

- `ProjectMap: Open File and Edit Annotation`: Opens a file and allows you to edit its annotation.
- `ProjectMap: Edit Folder Annotation`: Allows you to edit a folder's annotation.

## Configuration

You can configure ProjectMap through VS Code's settings:

- `projectdoc.autoSave`: Enable/disable auto-saving of annotations (default: true)

## File Storage

Annotations are stored in a `.projectmap-annotations.json` file in your project root. This file can be committed to version control to share annotations with your team.

## Requirements

- Visual Studio Code version 1.74.0 or higher

## Known Issues

- Annotations for files/folders ignored by `.gitignore` cannot be edited.

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Support

If you encounter any problems or have any suggestions, please [open an issue](https://github.com/Firebrand/projectmap/issues) on our GitHub repository.

---

Happy coding with ProjectMap! 🗺️👨‍💻👩‍💻